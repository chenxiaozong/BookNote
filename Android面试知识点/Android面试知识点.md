


### 1.DVM和JVM区别?

1. 执行文件类型 
    - jvm: 执行.class文件
    - dvm: 执行.dex文件; 抽取编译后的.class文件被dex工具抽取到一个.dex文件
2. 虚拟机类型
    - jvm: 基于虚拟栈的虚拟机 
    - dvm: 基于寄存器的虚拟机
3. 性能
    - .class文件存在冗余信息,dex会去除冗余信息,并把所有的.class文件整合到.dex文件中
    - 减少IO操作,提高了类查询速度 


### 2.Android安全机制
1. Android 是基于 Linux 内核的
> 因此 Linux 对文件权限的控制同样适用于 Android
在 Android 中每个应用都有自己的/data/data/包名 文件夹，该文件夹只能该应用访问，而其他应用则无权
访问。

2. Android 的权限机制保护了用户的合法权益  
> 如果我们的代码想拨打电话、发送短信、访问通信录、定位、访问 sdcard 等所有可能侵犯用于权益的行为都
是必须要在 AndroidManifest.xml 中进行声明的，这样就给了用户一个知情权。

3. Android 的代码混淆保护了开发者的劳动成果

### 3.Android 的四大组件都需要在清单文件中注册吗？

- Activity 、 Service 、 ContentProvider 如 果 要 使 用 则 必 须 在 AndroidManifest.xml 中 进 行 注 册
- BroadcastReceiver则有两种注册方式
    - 静态注册: 指在 AndroidManifest.xml 中进行
    - 动态注册: 代码中注册

### 4.在 Android中进程的级别有哪些？
a) Foreground process
b) Visible process
c) Service process
d) Background process
e) Empty process


### 5.Sp频繁操作有什么后果？sp 能存多少数据？（上海 3 期学员提供）
1. Sp 的底层是由 xml 来实现的，操作 sp 的过程就是 xml 的序列化和解析的过程。Xml 是存储在磁盘上的，因此考
虑到需要 I/O 速度问题，sp 不适宜频繁操作。

2. 同时序列化 xml 是就是将内存中的数据写到 xml 文件中，由于 dvm 的
内存是很有限的，因此单个 sp 文件不建议太大，具体多大是没有一个具体的要求的，但是我们知道 DVM 堆内存也就
是 16M，因此数据大小肯定不能超过这个数字的。
3. sp 设置的目的就是为了保存用户的偏好和配置信息的，因此不要保存太多的数据。





### 6.描述一下 Android 的系统架构（2017-2-23）
> android 系统架构分从下往上为 linux 内核层、运行库、应用程序框架层、和应用程序层

1. Linux内核层:linuxkernel：负责硬件的驱动程序、网络、电源、系统安全以及内存管理等功能。
2. libraries 和 androidruntime：
    - libraries：即 c/c++函数库部分，大多数都是开放源代码的函数库，
        - 例如webkit，该函数库负责 android 网页浏览器的运行，例如标准的 c 函数库 libc、openssl、sqlite 等
        - 当然也包括支持游戏开发 2dsgl 和 3dopengles，
        - 在多媒体方面有 mediaframework框架来支持各种影音和图形文件的播放与显示， 例如 mpeg4、 h.264、 mp3、aac、 amr、 jpg 和 png 等众多的多媒体文件格式。 
    - androidruntime: 负责解释和执行生成的 dalvik 格式的字节码。

3. applicationframework（应用软件架构），java 应用程序开发人员主要是使用该层封装好的 api 进行快速开发。
4. applications:该层是 java 的应用程序层，android 内置的 googlemaps、e-mail、即时通信工具、浏览器、mp3 播放 器等处于该层，java 开发人员开发的程序也处于该层，而且和内置的应用程序具有平等的位置，可以调用内置的应用程序，也可以替换内置的应用程序。



### 7.解释一下 Android 程序运行时权限与文件系统权限的区别？（2017-2-23）
> apk 程序是运行在虚拟机上的,对应的是 Android 独特的权限机制，只有体现到文件系统上时才使用 linux 的权限设置。


linux 文件系统上的权限如下表示,代表的是相应的用户/用户组及其他人对此文件的访问权限，与此文件运行起来具有的权限完全不相关。
`-rwxr-x--x system system 4156 2010-04-30 16:13 test.apk`

- system 用户拥有对此文件的rwx
- system 组的用户对此文件拥有r-x
- 其他人对此文件只具有--x。

而 test.apk 运行起来后可以干哪些事情，跟这个就不相关了。千万不要看 apk 文件系统上属于 system/system 用户及用户组，或者 root/root 用户及用户组，就认为 apk 具有 system 或 root 权限

> Android 的权限规则

- Android 中的 apk 必须签名
- 基于 UserID 的进程级别的安全机制
- 默认 apk 生成的数据对外是不可见的
- AndroidManifest.xml 中的显式权限声明

> 从 Android6.0 之后，Android 升级了权限机制，提出了动态权限的概念

### 8.Android6.0 的权限机制（2017-2-23）
1. 新权限思想
> Android 的权限系统一直是首要的安全概念，因为这些权限只在安装的时候被询问一次。一旦安装了，app 可以在用户毫不知晓的情况下访问权限内的所有东西，而且一般用户安装的时候很少会去仔细看权限列表，更不会去深入了解这些权限可能带来的相关危害。但是在Android 6.0 Marshmallow版本之后，系统不会在软件安装的时候就赋予该 app 所有其申请的权限，对于一些危险级别的权限，app 需要在运行时一个一个询问用户授予权限

2. 对旧版本 App 的兼容
> 那么问题来了，是不是所有以前发布的 app 都会出现问题呢？答案是不会
- 只有那些 targetSdkVersion 设置为23 及以上的应用才会出现异常，在使用危险权限的时候系统必须要获得用户的同意才能使用，要不然应用就会崩溃，
出现类似下面的错误。`java.lang.SecurityException: Permission Denial... ` 

- 所以 targetSdkVersion 如果没有设置为 23 版本或者以上，系统还是会使用旧规则：(在安装的时候赋予该 app 所
申请的所有权限)所以 app 当然可以和以前一样正常使用了，但是还有一点需要注意的是 6.0 的系统里面，用户可以
手动将该 app 的权限关闭，在 App info 里面 Permissions 下边，可以关闭某个权限。如果以前的老应用申请的权限
被用户手动关闭了，不会抛出异常，不会崩溃，只不过调用那些被用户禁止权限的 api 接口返回值都为 null 或者 0，
所以我们只需要做一下判空操作就可以了，这是需要注意的

3.普通权限和危险权限列表



### 9.两Activity之间传递数据: 
1. Intent/BroadcastReceiver/ContentProvider
2. 其它方式
- 静态数据:public static
- 外部文件存储
    + File
    + SharePrefrence
    + Sqlite
- EnventBus(不跨进程) 
- 剪贴板



