[TOC]

目录
# 第1章Java语言概述与开发环境1 
## 1.1Java语言的发展简史2 
## 1.2Java的竞争对手及各自优势4 
 1.2.1C#简介和优势4 
 1.2.2Ruby简介和优势5 
 1.2.3Python简介和优势5 
## 1.3Java程序运行机制6 
 1.3.1高级语言的运行机制6 
 1.3.2Java程序的运行机制和JVM6 
## 1.4开发Java的准备8 
 1.4.1下载和安装Java8的JDK8 
 1.4.2设置PATH环境变量10 
## 1.5第一个Java程序12 
 1.5.1编辑Java源代码12 
 1.5.2编译Java程序12 
 1.5.3运行Java程序13 
 1.5.4根据CLASSPATH环境变量定位类14 
## 1.6Java程序的基本规则15 
 1.6.1Java程序的组织形式15 
 1.6.2Java源文件的命名规则16 
 1.6.3初学者容易犯的错误17 
## 1.7垃圾回收机制19 
## 1.8何时开始使用IDE工具20 
## 1.9本章小结21 
# 第2章 理解面向对象22 
## 2.1面向对象23 
2.1.1结构化程序设计简介23 
2.1.2程序的三种基本结构24 
2.1.3面向对象程序设计简介26 
2.1.4面向对象的基本特征27 
## 2.2UML（统一建模语言）介绍28 
2.2.1用例图30 
2.2.2类图30 
2.2.3组件图32 
2.2.4部署图33 
2.2.5顺序图33 
2.2.6活动图34 
2.2.7状态机图35 
## 2.3Java的面向对象特征36 
2.3.1一切都是对象36 
2.3.2类和对象36 
## 2.4本章小结37 
# 第3章 数据类型和运算符38 
## 3.1注释39 
3.1.1单行注释和多行注释39 
3.1.2文档注释40 
API文档是什么？40 
为什么要学习查看API文档的方法？ 
## 3.2标识符和关键字46 
3.2.1分隔符46 
3.2.2标识符规则47 
3.2.3Java关键字47 
## 3.3数据类型分类48 
什么是变量？变量有什么用？48 
## 3.4基本数据类型49 
3.4.1整型49 
3.4.2字符型51 
什么是字符集？51 
3.4.3浮点型53 
3.4.4数值中使用下画线分隔54 
3.4.5布尔型54 
## 3.5基本类型的类型转换55 
3.5.1自动类型转换55 
3.5.2强制类型转换56 
3.5.3表达式类型的自动提升58 
## 3.6直接量59 
3.6.1直接量的类型59 
3.6.2直接量的赋值59 
## 3.7运算符60 
3.7.1算术运算符60 
3.7.2赋值运算符63 
3.7.3位运算符63 
3.7.4扩展后的赋值运算符66 
3.7.5比较运算符66 
3.7.6逻辑运算符67 
3.7.7三目运算符68 
3.7.8运算符的结合性和优先级69 
## 3.8本章小结70 
# 第4章 流程控制与数组71 
4.1顺序结构72 
4.2分支结构72 
4.2.1if条件语句72 
4.2.2Java7增强后的switch分支语句76 
4.3循环结构78 
4.3.1while循环语句78 
4.3.2dowhile循环语句79 
4.3.3for循环80 
4.3.4嵌套循环83 
4.4控制循环结构84 
4.4.1使用break结束循环84 
4.4.2使用continue忽略本次循环剩下 
语句85 
4.4.3使用return结束方法86 
4.5数组类型86 
4.5.1理解数组：数组也是一种类型86 
int[]是一种类型吗？怎么使用这种类型呢？87 
4.5.2定义数组87 
4.5.3数组的初始化88 
能不能只分配内存空间，不赋初始值呢？88 
4.5.4使用数组89 
为什么要我记住这些异常信息？89 
4.5.5foreach循环90 
4.6深入数组91 
4.6.1内存中的数组91 
为什么有栈内存和堆内存之分？92 
4.6.2基本类型数组的初始化94 
4.6.3引用类型数组的初始化95 
4.6.4没有多维数组97 
我是否可以让图4.13中灰色覆盖的数组元素再次指向另一个数组？这样不就可以扩展成三维数组，甚至扩展成更多维的数组吗？98 
4.6.5Java8增强的工具类：Arrays99 
4.6.6数组的应用举例102 
4.7本章小结105 
本章练习105 
# 第5章 面向对象（上）106 
## 5.1类和对象107 
5.1.1定义类107 
构造器不是没有返回值吗？为什么不能用void声明呢？109 
5.1.2对象的产生和使用110 
5.1.3对象、引用和指针110 
5.1.4对象的this引用111 
## 5.2方法详解115 
5.2.1方法的所属性115 
5.2.2方法的参数传递机制116 
5.2.3形参个数可变的方法119 
5.2.4递归方法120 
5.2.5方法重载122 
为什么方法的返回值类型不能用于区分重载的方法？122 
## 5.3成员变量和局部变量123 
5.3.1成员变量和局部变量123 
5.3.2成员变量的初始化和内存中的 
运行机制126 
5.3.3局部变量的初始化和内存中的 
运行机制128 
5.3.4变量的使用规则129 
## 5.4隐藏和封装130 
 5.4.1理解封装130 
> 封装是面向对象的三大特性之一(封装/继承/多态)

- 封装: 指将对象的状态信息隐藏在对象内部,不允许程序直接访问对象的内部信息,而是通过该类所提供的方法(接口)实现对内部信息的访问和操作

> 良好的封装能实现以下目的:

- ① 隐藏类的实现细节
- ② 让使用者只能通过事先预定的方法来访问数据,从而可以在方法里加入控制逻辑(限制/检查)限制对成员变量的不合理访问(操作)
- ③ 进行数据检查,保证对象的信息完整性
- ④ 便于修改,提高代码的可维护性

> 实现良好的封装: (该隐藏的隐藏,该暴露的暴露)

- 把对象的成员变量和实现细节隐藏起来,不允许直接访问
- 把方法暴露出来,使用方法实现对成员变量的访问和操作

 5.4.2使用访问控制符130 



 5.4.3package、import和importstatic133 
 5.4.4Java的常用包138 
## 5.5深入构造器138 
 5.5.1使用构造器执行初始化138 
 5.5.2构造器重载139 
## 5.6类的继承141 
> 继承是面向对象的三大特性之一,是实现软件复用的重要手段. Java继承是单继承,每个子类只有一个父类

5.6.1继承的特点141 
5.6.2重写父类的方法142 
5.6.3super限定144 
5.6.4调用父类构造器146 
## 5.7多态148 
5.7.1多态性148 
5.7.2引用变量的强制类型转换150 
5.7.3instanceof运算符151 
5.8继承与组合152 
5.8.1使用继承的注意点152 
5.8.2利用组合实现复用153 
使用组合关系来实现复用时，需要创建两个Animal对象，是不是意味着使用组合关系时系统开销更大？156 
5.9初始化块156 
5.9.1使用初始化块156 
5.9.2初始化块和构造器158 
5.9.3静态初始化块159 
5.10本章小结161 
# 第6章 面向对象（下）162 
6.1Java8增强的包装类163 
Java为什么要对这些数据进行缓存呢？166 
6.2处理对象167 
6.2.1打印对象和toString方法167 
6.2.2==和equals方法169 
上面程序中判断obj是否为Person类的实例时，为何不用objinstanceofPerson来判断呢？172 
6.3类成员172 
6.3.1理解类成员172 
6.3.2单例（Singleton）类173 
6.4final修饰符174 
6.4.1final成员变量175 
6.4.2final局部变量176 
6.4.3final修饰基本类型变量和引用类 
型变量的区别177 
6.4.4可执行“宏替换”的final变量178 
6.4.5final方法180 
6.4.6final类180 
6.4.7不可变类181 
6.4.8缓存实例的不可变类183 
6.5抽象类186 
6.5.1抽象方法和抽象类186 
6.5.2抽象类的作用189 
6.6Java8改进的接口190 
6.6.1接口的概念190 
6.6.2Java8中接口的定义190 
6.6.3接口的继承193 
6.6.4使用接口193 
6.6.5接口和抽象类195 
6.6.6面向接口编程195 
6.7内部类199 
6.7.1非静态内部类199 
非静态内部类对象和外部类对象的关系是怎样的？203 
6.7.2静态内部类203 
为什么静态内部类的实例方法也不能访问外部类的实例属性呢？204 
接口里是否能定义内部接口？205 
6.7.3使用内部类205 
既然内部类是外部类的成员，那么是否可以为外部类定义子类，在子类中再定义一个内部类来重写其父类中的内部类呢？208 
6.7.4局部内部类208 
6.7.5Java8改进的匿名内部类209 
6.8Java8新增的Lambda表达式212 
6.8.1Lambda表达式入门212 
6.8.2Lambda表达式与函数式接口214 
6.8.3方法引用与构造器引用216 
6.8.4Lambda表达式与匿名内部类的 
联系和区别218 
6.8.5使用Lambda表达式调用Arrays 
的类方法219 
6.9枚举类220 
6.9.1手动实现枚举类220 
6.9.2枚举类入门221 
6.9.3枚举类的成员变量、方法和构造器222 
6.9.4实现接口的枚举类224 
枚举类不是用final修饰了吗？怎么还能派生子类呢？225 
6.9.5包含抽象方法的枚举类225 
6.10对象与垃圾回收226 
6.10.1对象在内存中的状态227 
6.10.2强制垃圾回收227 
6.10.3finalize方法229 
6.10.4对象的软、弱和虚引用230 
6.11修饰符的适用范围233 
6.12使用JAR文件234 
6.12.1jar命令详解235 
6.12.2创建可执行的JAR包236 
6.12.3关于JAR包的技巧237 
6.13本章小结238 
本章练习238 
# 第7章 Java基础类库239 
7.1与用户互动240 
7.1.1运行Java程序的参数240 
7.1.2使用Scanner获取键盘输入241 
7.2系统相关243 
7.2.1System类243 
7.2.2Runtime类245 
7.3常用类246 
7.3.1Object类246 
7.3.2Java7新增的Objects类247 
7.3.3String、StringBuffer和 
StringBuilder类248 
7.3.4Math类251 
7.3.5Java7的ThreadLocalRandom 
与Random253 
7.3.6BigDecimal类255 
7.4Java8的日期、时间类257 
7.4.1Date类257 
7.4.2Calendar类258 
7.4.3Java8新增的日期、时间包261 
7.5正则表达式263 
7.5.1创建正则表达式263 
7.5.2使用正则表达式266 
7.6国际化与格式化270 
7.6.1Java国际化的思路270 
7.6.2Java支持的国家和语言270 
7.6.3完成程序国际化271 
7.6.4使用MessageFormat处理包含占 
位符的字符串273 
7.6.5使用类文件代替资源文件274 
7.6.6使用NumberFormat格式化数字274 
7.6.7使用DateFormat格式化日期、时间276 
7.6.8使用SimpleDateFormat格式化日期277 
7.7Java8新增的日期、时间格式器278 
7.7.1使用DateTimeFormatter完成格式化278 
7.7.2使用DateTimeFormatter解析字符串279 
7.8本章小结280 
本章练习280 

----
# 第8章 Java集合281 
> Java集合是一种特别有用的工具类

- ① 用来存储数量不等的对象
- ② 并可以实现常用的数据结构(如:栈,队列)
- ③ 保存具有映射关系的关联数组

> java集合元素分为四中体系

- Set : 无序的,不可重复的
- List: 有序,可重复
- Queue: 代表一种队列集合实现,(java5增加)
- Map : 具有映射关系的集合

## 8.1Java集合概述282 
> 集合主要负责保存,程装其他数据,因此,集合也称为容器类.

- java集合由两个接口派生
    + Collection
        * Set(接口:无序集合,不可重复)
            - EnumSet(接口)
            - SortedSet(接口)
                + **TreeSet**(有序)
            - **HashSet**
                + LinckedHashSet
        * Queue(接口:队列)
            - Dequen()
                + **ArrayDequeue**
            - PriorityQueue
        * List(接口:有序集合,元素可以重复)
            - **LinckedList**
            - **ArrayList**
            - Vector
                + Stack
    + Map(接口:保存具有映射关系的数据)-map保存的每项数据都是一个key-value对
        * EnumMap
        * IdentityHashMap
        * **HashMap**(线程不安全,key-value允许为null)
            - LinckedHashMap
        * HashTable(线程安全,key-value不允许为null)
        * SortedMap
            - **TreeMap** 
        * WeakHashMap
    


## 8.2Collection和Iterator接口283 
> Collection 接口是List/set/queue的父接口,Collection接口中定义了常用的集合操作的方法


| 方法 | 作用 |
| ------------- | ------------- |
| boolean add(Object obj)   | 向集合中添加元素 |
boolean addAll(Collection<? extends E> c) | 将集合c 中的元素添加到集合中
void clear() | 清除集合中所有元素-->长度变为0
boolean contains(Object o) | 集合中是否包含o? 
boolean containsAll(Collection<?> c) | 集合中是否包含集合c中所有元素
boolean isEmpty()  | 返回集合是否为空
Iterator<E> iterator() |返回一个iterator 用于遍历集合元素
boolean remove(Object o)    | 集合中删除o
boolean removeAll(Collection<?> c)| 从集合中删除存在的c中的所有元素
boolean retainAll(Collection<?> c)| 集合中删除所有不在c中包含的元素(删除所有元素,只保留c中的元素)
int size() | 集合元素个数
Object[] toArray() | 转化为数组
default boolean removeIf(Predicate<? super E> filter)| 删除符合条件的元素 如条件:(obj->((String)obj).length()>=8)

> 常用集合操作(遍历)

- ① 使用iterator遍历
- ② 使用Lambda表达式遍历
- ③ 使用Lambda增强的iterator遍历
- ④ 使用增强for循环
- ⑤ 使用Predicate操作集合

```java
    @org.junit.Test
    public void test() {
        Collection<String> books = new HashSet();
        books.add("Java疯狂讲义");
        books.add("Android疯狂讲义");
        books.add("Struts疯狂讲义");
        System.out.println(books);
        //使用iterator遍历
        Iterator iterator = books.iterator();
        while (iterator.hasNext()){
            String next = (String) iterator.next();
            System.out.println(next);
        }
        //使用Lambda表达式
        books.forEach(obj-> System.out.println(obj));
        //3.使用Lambda增强的iterator遍历
        System.out.println("=========使用Lambda增强的iterator遍历============");
        Iterator lambIterator = books.iterator();
        lambIterator.forEachRemaining(obj-> System.out.println(obj));
        //4. 使用增强for循环
        System.out.println("=========4. 使用增强for循环============");
        for (String book:books){
            System.out.println(book+" length:"+book.length());
        }
        //5. 使用Predicate操作集合
        System.out.println("========使用Predicate操作集合========");
//        books.removeIf(elm->"表达式过滤"));
        books.removeIf(elm->(elm.length()>8));
        books.forEach(obj-> System.out.println(obj));
    }
```



8.2.1使用Lambda表达式遍历集合285 
> Java8 为Iterable 接口提供了一个forEach(Conumer action) 默认方法.该方法的参数类型是一个函数式接口. 而Iterable接口是Collection接口的父接口,因此Collection集合也可以直接调用该接口

- 使用Lambda表达式遍历集合元素
```java
//使用Lambda表达式
        books.forEach(obj-> System.out.println(obj));
```

8.2.2使用Java8增强的Iterator遍历集 合元素286 

> Iterator 接口也是Java集合框架的成员,但它与 Collection 系列,Map 系列的集合不一样,Iterator 主要用于遍历访问 Collection 集合元素


- Iterator接口四个方法 

| 方法 | 作用 |
| ------------- | ------------- |
default void **forEachRemaining** (Consumer<? super E> action) |使用Lambda表达式遍历集合元素
boolean **hasNext()**  | Returns true if the iteration has more elements.
Object  **next()**  |Returns the next element in the iteration.
default void **remove()** | Removes from the underlying collection the last element returned by this iterator (optional operation).


- 使用Java8 iterator遍历
```java
        //使用iterator遍历
        Iterator iterator = books.iterator();
        while (iterator.hasNext()){
            String next = (String) iterator.next();
            System.out.println(next);
        }
```


 8.2.3使用Lambda表达式遍历Iterator287 
```java
   //3.使用Lambda增强的iterator遍历
        System.out.println("=========使用Lambda增强的iterator遍历============");
        Iterator lambIterator = books.iterator();
        lambIterator.forEachRemaining(obj-> System.out.println(obj));

```


8.2.4使用foreach循环遍历集合元素288 
```java
  //4. 使用增强for循环
        System.out.println("=========4. 使用增强for循环============");
        for (String book:books){
            System.out.println(book+" length:"+book.length());
        }
```


8.2.5使用Java8新增的Predicate操作集合288 
>  **removeIf("验证条件")** 


 ```java
     //5. 使用Predicate操作集合
        System.out.println("========使用Predicate操作集合========");
//        books.removeIf(elm->"表达式过滤"));
        books.removeIf(elm->(elm.length()>8));
        books.forEach(obj-> System.out.println(obj));

 ```
 
> 使用Predicate操作集合
1. 统计集合中"Java"出现的次数
2. 统计集合中"疯狂"出现的次数
3. 统计集合中长度>10的eml出现的次数

```java
        Collection<String> books = new HashSet();
        books.add("Java疯狂讲义");
        books.add("Android疯狂讲义");
        books.add("Struts疯狂讲义");
        books.add("Ajax疯狂讲义");
        books.add("Ios疯狂讲义");
        books.add("JavaEE疯狂讲义");
        int javaCount = predicateBookSet(books, elm -> ((String) elm).contains("Java"));//返回包含"Java"的记录的条数
        int fkCount = predicateBookSet(books, elm -> ((String) elm).contains("疯狂"));//返回包含"疯狂"的记录的条数
        int lenCount = predicateBookSet(books, elm -> ((String) elm).length()>8);////3. 统计集合中长度>8的eml出现的次数

```

> 统计符合验证条件的数据

```java
    private int predicateBookSet(Collection<String> books, Predicate p) {
        int count = 0;//统计计数
        for (Object book:books){
            boolean test = p.test(book);//使用predicate验证book是否满足条件
            if (test){
                count++;
            }
        }
        return count;
    }
```


8.2.6使用Java8新增的Stream操作集合289 

> Stream常用方法

| 方法 | 作用 |
| ------------- | ------------- |
boolean allMatch(Predicate<? super T> predicate) |Returns whether all elements of this stream match the provided predicate.
boolean anyMatch(Predicate<? super T> predicate)| Returns whether any elements of this stream match the provided predicate.
DoubleStream    mapToDouble(ToDoubleFunction<? super T> mapper)|Returns a DoubleStream consisting of the results of applying the given function to the elements of this stream.
IntStream   mapToInt(ToIntFunction<? super T> mapper)| Returns an IntStream consisting of the results of applying the given function to the elements of this stream.
LongStream  mapToLong(ToLongFunction<? super T> mapper)| Returns a LongStream consisting of the results of applying the given function to the elements of this stream.

> Stream操作集合

```java
     int sum = widgets.stream()
                      .filter(w -> w.getColor() == RED)//过滤
                      .mapToInt(w -> w.getWeight())//映射到新的集合
                      .count()//统计个数
                      .sum();//求和
```



```java
  //3. 使用Stream操作集合
        //统计集合books中"Java"出现的次数
//        Stream<String> stream = books.stream();//将books-->Stream
        long count = books.stream().filter(elm -> ((String) elm).contains("Java")).count();
        long fkStreamCount = books.stream().filter(elm -> ((String) elm).contains("疯狂")).count();
        long lenStreamCount = books.stream().filter(elm -> ((String) elm).length()>=8).count();
        //将books中数据字符串的长度重新映射到一个int集合
        IntStream intStream = books.stream().mapToInt(elm -> ((String) elm).length());
        System.out.println("----将books中数据字符串的长度重新映射到一个int集合-----");
//        intStream.forEach(in-> System.out.print(in+" "));
        intStream.forEach(System.out::println);
        System.out.println("Java出现次数:"+count);
        System.out.println("疯狂出现次数:"+fkStreamCount);
        System.out.println("长度大于等于8出现次数:"+lenStreamCount);
```



## 8.3Set集合291 
> Set集合不允许包含相同的元素

8.3.1HashSet类292 
- 按Hash算法存储集合中的元素,具有良好的存取和查询性能

> 特点

- 不能保证元素的排列顺序(存储顺序可能和插入数据的顺序不同)
- 不是同步的,必须通过同步代码保证其同步
- 集合元素值可以为null


8.3.2LinkedHashSet类295 

- HashSet的子类,通过hashCode值决定元素的存储位置,
- 使用链表维护元素次序,按元素插入顺序排列
- 需要维护元素的插入顺序,性能略低于HashSet
- 以链表维护,迭代访问时有很好的性能
- 同HashSet 一样,不能有重复元素



8.3.3TreeSet类296 
> TreeSet 是 SortedSet 接口的实现类,集合元素处于有序状态


- TreeSet额外方法(与HashSet集合相比)

| 方法 | 作用 |
| ------------- | ------------- |
public Comparator<? super E> comparator() | 如果使用了定制排序,返回定制排序的comparator;如果使用自然排序,返回null
first() | 返回第一个元素
last() | 返回集合中最后一个元素
lower() |返回集合中指定元素只前的(最大的)一个元素
higher() | 返回集合中比指定元素大的元素中的(最小的一个)
subSet(from, to) | 返回集合的子集合 [from,to)
headSet(toEml) | 返回set的头开始子集,由小于toEml 的元素组成
tailSet(from) |  返回set尾子集 由大于from的元素组成


> 测试

```java
TreeSet <Integer> set = new TreeSet<>();

        for (int i=0;i<10;i++){
            set.add(10-i);
        }
        System.out.println(set);


        System.out.println("第一个元素:"+set.first());

        System.out.println("最后一个元素:" + set.last());
        System.out.println("大于6的第一个元素:" + set.higher(6));
        System.out.println("小于4的第一个元素:" + set.lower(4));
        System.out.println("3-7的子串:" + set.subSet(3, 7));

        System.out.println("头子集到3(不包含):"+set.headSet(3));//头子集
        System.out.println("尾子集5(包含)起:"+set.tailSet(5));//尾子集

```

```java
第一个元素:1
最后一个元素:10
大于6的第一个元素:7
小于4的第一个元素:3
3-7的子串:[3, 4, 5, 6]
头子集到3(不包含):[1, 2]
尾子集5(包含)起:[5, 6, 7, 8, 9, 10]
```

① 自然排序 - TreeSet 会调用集合的CompareTo(obj) 方法来比较元素的大小,然后将集合的元素按 **升序** 排序

- result = obj1.compareTo(obj2): 返回值三种状态
    + result==0: obj1==obj2
    + result>0: obj1 > obj2 
    + result<0: obj1 < obj2

> Java中一些常用类实现了Commparable接口

- BigDecimal,BigInteger 以及所有数值型对应的包装类
- Character : 按Unicode 值进行比较
- Boolean : true > false
- String : 按String 字符对应的Unicode 值进行比较
- Date,Time: 后面的时间,日期,比前面的大

> 说明:

- 如果试图把一个对象添加到TreeSet中,则该对象必须实现Comparable接口,否则抛出异常 (第一个元素可以添加,添加第二个元素时抛出异常)
- 同一个treeset中添加的对象必须是同一个类的对象,否则抛出异常(原因:调用compareTo(obj))
- 若待加入的元素在集合中已经存在,则不再进行添加操作(set中元素不可重合)

② 定制排序

- 1. 自定义对象定制排序(指定Comparator)

```java
    /**
     * 使用Treeset定制排序
     */
    @Test
    public void testSustormSort(){
        TreeSet<Person> personSet = new TreeSet<>(new Comparator<Person>() {
            @Override
            public int compare(Person o1, Person o2) {
//                return o1.age>o2.age? 1:o1.age<o2.age?-1:0;//根据年龄排序从小到大排序
                return o1.age<o2.age?1:o1.age > o2.age? -1:0;//根据年龄从大到小排序
            }
        });
        personSet.add(new Person(5,"aaa"));
        personSet.add(new Person(22,"bbb"));
        personSet.add(new Person(4,"ccc"));
        personSet.add(new Person(33,"ddd"));
        personSet.add(new Person(1,"eee"));
        System.out.println(personSet.toString());
    }
    class  Person{
        int age ;
        String name ;
        public Person(int age, String name) {
            this.age = age;
            this.name = name;
        }
        @Override
        public String toString() {
            return "Person{" +
                    "age=" + age +
                    ", name='" + name + '\'' +
                    '}';
        }
    }
```


- 2.使用TreeSet从小到大排序(指定Comparator)


```java
/**
     * 使用Treeset定制排序:
     * 常用数据类型从大到小排序
     */
    @Test
    public void testSustormSort2(){
        TreeSet<Integer> inset = new TreeSet<>(new Comparator<Integer>() {
            @Override
            public int compare(Integer o1, Integer o2) {
//                //从大到小排序
//                if (o1>o2){
//                    return -1;
//                }else if (o1==o2){
//                    return 0;
//                }else {
//                    return 1;
//                }
                return o1>o2?-1:o1==o2?0:1;
            }
        });
        for (int i = 0;i<10;i++){
            inset.add(i);
        }
        System.out.println(inset.toString());
    }
```


**8.3.4EnumSet类302 ** 

> EnumSet是一个专门为枚举类设计的集合类,其所有元素必须是指定枚举类型的枚举值.该枚举类型在创建EnumSet时显式或隐式指定.

- EnumSet的集合元素是有序的
- 元素顺序按照枚举值在Enum类内定义的顺序决定
- EnumSet在内部是以位向量的形式存储,这种存储方式非常紧凑,高效,因此枚举集合对象占用空间很小,效率高
- EnumSet集合不允许加入null元素
- EnumSet没有暴露任何构造器创建枚举集合对象,而是使用其提供的 **类方法** 创建

> EnumSet常用方法

| 方法 | 作用 |
| ------------- | ------------- |
| allOf(Class elmType) | 创建一个指定枚举类所有枚举值的集合对象|
complementOf(EnumSet s) | 创建一个元素类型与指定EnumSet s 里元素类型相同的EnumSet集合,新EnumSet包含原集合s所不包含的所有枚举值(即新集合+s 是当前枚举类所有枚举值)
copyOf(Collection c) | 用一个普通集合创建EnumSet集合
copyOf(EnumSet e) | 创建一个与指定枚举集合具有相同元素,相同类型的枚举集合
noneOf(Class elemType) | 创建一个元素类型为指定枚举类型的空的枚举集合
of(E first ,E...res) | 创建一个包含或多个枚举值的EnumSet集合,传入的多个枚举值必须属于同一个枚举类
range(E from ,E to) | 创建一个从from 到to 枚举值范围内的所有枚举值的EnumSet集合



> 创建枚举集合


```java
EnumSet<Season> seasonsEnumSet = EnumSet.allOf(Season.class);
        //包含Season枚举类的所有枚举值的枚举集合
        System.out.println(seasonsEnumSet);
        //2.创建一个空的 Season枚举类的枚举集合
        EnumSet<Season> noneOf = EnumSet.noneOf(Season.class);
        System.out.println(noneOf);
        noneOf.add(Season.fall);//向枚举集合中添加枚举值
        System.out.println(noneOf);
        //3.从一个枚举集合创建枚举集合
        EnumSet<Season> copy = EnumSet.copyOf(seasonsEnumSet);
        System.out.println(copy);
        //4. 指定枚举集合
        EnumSet<Season> ofEnum = EnumSet.of(Season.spring, Season.fall);
        System.out.println(ofEnum);
        //5. 指定范围
        EnumSet<Season> range = EnumSet.range(Season.spring, Season.fall);
        System.out.println(range);
        //6. 使用指定枚举集合的补集
        EnumSet<Season> complementOf = EnumSet.complementOf(ofEnum);
        System.out.println(complementOf);
```

> 输出

```
[spring, summery, fall, winter]
[]
[fall]
[spring, summery, fall, winter]
[spring, fall]
[spring, summery, fall]
[summery, winter]
```



**8.3.5 各Set实现类的性能分析303 ** 

> 比较HashSet ,TreeSet,EnumSet

| HashSet | TreeSet 
| ------------- | ------------- | ------------- |



| 集合类型 |  说明 |
| ------------- | ------------- |
| HashSet |① HashSet的性能总是比TreeSet好(特别是添加,查询等操作),元素顺序与插入顺序不一定对应  ②子类LinckedHashSet插入删除比HashSet略慢,使用链表维护,遍历速度快,并且元素顺序与插入顺序对应| 
| TreeSet |① 需要通过红黑色维持有序,只有当需要一个有序集合时房使用,否则使用HashSet  ②TreeSet元素有序(可以自定义Comparable按指定方式排序)| 
| EnumSet| ① 所有set中性能最好  ②只能保存同一个枚举类的枚举值| 

> 说明:Set的三个实现类HashSet TreeSet 和 EnumSet 都是线程不安全的;通常使用Collections的synchronizedSortedSet 方法包装set集合实现同步访问

`SortedSet <Integer> sortedSet = Collections.synchronizedSortedSet(new TreeSet<>());` 




## 8.4List集合304 
> List 集合代表元素 **有序,可重复**  的集合,集合中每个元素都有其对应的 **顺序** 索引.

- List 集合允许使用重复元素
- 通过索引访问指定位置的集合元素
- 默认按元素的添加顺序设置元素的索引

**8.4.1 Java8改进的List接口和ListIterator接口304 ** 
> List作为 collection的子接口,可以使用 collection接口的全部方法,同时List是有序集合,List添加了一些根据索引操作集合元素的方法

| 方法 | 作用 |
| ------------- | ------------- |
| add(index,obj ) | 将元素添加到list集合的index索引位置|
addAll(index,Collection c) | 将集合C所包含的元素都插入到list的index索引处
get(index  )| 获取index索引处的值
indexOf( Object o ) | 返回o第一次出现的位置
lastIndexOf(Object o ) | 返回o最后一次出现的位置
remove(index ) | 移除index索引处的元素
set(index ,Object o) | 替换元素
subList(int from,int to) | 返回指定范围的子list集合[from ,to)
replaceAll(UnaryOperator operator) | 根据 operator 计算规则,重新设置list集合的所有元素
sort(Comparator c) | 根据 Comparator参数,对集合进行排序

- ① List常用操作:

```java
List<String> books = new ArrayList<>();
        books.add("Java疯狂讲义");
        books.add("Androdi疯狂讲义");
        books.add("IOS疯狂讲义");
        books.add("Ajax疯狂讲义");
        books.add("web疯狂讲义");
        books.add("jsp疯狂讲义");
        books.add("jsp疯狂讲义..........");
        System.out.println(books);
        books.set(4,"Web疯狂讲义");//设置元素
        System.out.println(books);
        int ios = books.indexOf(new String("IOS疯狂讲义"));
        System.out.println("iso的index:" + ios);
        int ajax = books.lastIndexOf("Ajax疯狂讲义");
        System.out.println("lastIndex_Ajax:" + ajax);
        books.remove(new String("Java疯狂讲义"));//List匹配元素是根据equals 方法此处会删除第一个元素
        System.out.println("iso的index:" + ios);
```


- ② List的排序方法  使用Comparable
    + 排序1:使用Comparator
    + 排序2:根据字符串长度有长到短
    + 排序3:使用Lambda表达式作为Comparable参数



```java
        //排序 :使用Comparator
        books.sort(new Comparator<String>() {
            @Override
            public int compare(String o1, String o2) {
                return  o1.compareTo(o2);
            }
        });
        System.out.println("排序后:"+books);
        //排序:根据字符串长度有长到短
        books.sort(new Comparator<String>() {
            @Override
            public int compare(String o1, String o2) {
                return o1.length()-o2.length();//根据字符串长度排序
                //return o1.length()>o2.length()?1:o1.length()==o2.length()?0:-1;
            }
        });
        System.out.println("根据字符串长度排序:" + books);
        //排序3:使用Lambda表达式作为Comparable参数
        books.sort((o1,o2)->((String)o2).length()-((String)o1).length());
        System.out.println("根据字符串长度排序(从长到短):" + books);

```

- ③ 使用List的replaceAll,操作集合元素
    + 替换成字符串的长度


```java
//list的replaceAll() - 需要一个UnaryOperator 来替换所有集合元素
        books.replaceAll(new UnaryOperator<String>() {
            @Override
            public String apply(String s) {
                return s.length()+"";
            }
        });
        System.out.println("替换为字符串的长度:"+books);//[17, 11, 8, 7, 7, 7]
        //UnaryOperator 也是一个函数式接口,可以使用Lanmbda 表达式作为参数
        //替换Lambda
        books.replaceAll(elm->((String)elm).length()+"");
        System.out.println("替换为字符串的长度Lambda:"+books);
```




- ④ List提供listIterator() 方法;返回一个ListIterator对象,ListIterator继承了 Iterator接口,提供了专门list的操作方法
> ListIterator 相比普通Iterator 
① 增加了前行迭代的功能   
② 可以添加元素

| 方法 | 作用 |
| ------------- | ------------- |
| hasPrevious() | 是否还有上一个元素 |
| previous() | 返回上一个元素 |
| add(Object obj) | 在指定位置插入 |

> List使用使用 Iterator 和ListIterator(可以前向迭代,可以添加元素)

```java
       //1. List使用Collection 的 Iterator
        System.out.println("---------------List使用Iterator-----------------");
        Iterator<String> iterator = books.iterator();
        while (iterator.hasNext()){
            System.out.println(iterator.next());
        }

        //2. List使用ListIterator后向遍历
        System.out.println("---------------List使用ListIterator-----------------");

        ListIterator<String> listIterator = books.listIterator();
        while (listIterator.hasNext()){
            System.out.println(listIterator.next());
        }


        //3. List使用ListIterator(前向迭代)
        System.out.println("---------------List使用ListIterator(前向迭代)-----------------");

        while (listIterator.hasPrevious()){
            System.out.println(listIterator.previous());
        }


        //4.List使用ListIterator(添加元素到list)
        System.out.println("---------------List使用ListIterator(添加元素到list)-----------------");
        ListIterator<String> stringListIterator = books.listIterator();
        while (stringListIterator.hasNext()){
            System.out.println(stringListIterator.next());
            stringListIterator.add("--分隔符---");
        }

        while (stringListIterator.hasPrevious()){
            System.out.println(stringListIterator.previous());
        }
```



**8.4.2 ArrayList和Vector实现类307** 
ArrayList和Vector作为List的两个典型实现,


8.4.3固定长度的List308 
## 8.5Queue集合308 
8.5.1PriorityQueue实现类309 
8.5.2Deque接口与ArrayDeque实现类309 
8.5.3LinkedList实现类311 
8.5.4各种线性表的性能分析312 
## 8.6Java8增强的Map集合313 
8.6.1Java8为Map新增的方法315 
8.6.2Java8改进的HashMap和Hashtable实现类316 
8.6.3LinkedHashMap实现类319 
8.6.4使用Properties读写属性文件319 
8.6.5SortedMap接口和TreeMap实现类320 
8.6.6WeakHashMap实现类323 
8.6.7IdentityHashMap实现类323 
8.6.8EnumMap实现类324 
8.6.9各Map实现类的性能分析325 
## 8.7HashSet和HashMap的性能选项325 
## 8.8操作集合的工具类：Collections326 
8.8.1排序操作326 
8.8.2查找、替换操作329 
8.8.3同步控制330 
8.8.4设置不可变集合330 
## 8.9烦琐的接口：Enumeration331 
## 8.10本章小结332 
## 本章练习332 



--- 

# 第9章 泛型333 
9.1泛型入门334 
9.1.1编译时不检查类型的异常334 
9.1.2使用泛型334 
9.1.3Java7泛型的“菱形”语法335 
9.2深入泛型336 
9.2.1 定义泛型接口、类336 
9.2.2从泛型类派生子类338 
9.2.3并不存在泛型类339 
9.3类型通配符339 
9.3.1使用类型通配符341 
9.3.2设定类型通配符的上限341 
9.3.3设定类型形参的上限343 
9.4泛型方法344 
9.4.1定义泛型方法344 
9.4.2泛型方法和类型通配符的区别346 
9.4.3Java7的“菱形”语法与泛型构 
造器347 
9.4.4设定通配符下限348 
9.4.5泛型方法与方法重载350 
9.4.6Java8改进的类型推断351 
9.5擦除和转换352 
9.6泛型与数组353 
9.7本章小结355 
# 第10章 异常处理356 
10.1异常概述357 
10.2异常处理机制358 
10.2.1使用try...catch捕获异常358 
10.2.2异常类的继承体系360 
10.2.3Java7提供的多异常捕获362 
10.2.4访问异常信息363 
10.2.5使用finally回收资源364 
10.2.6异常处理的嵌套366 
10.2.7Java7的自动关闭资源的try语句366 
10.3Checked异常和Runtime异常体系368 
10.3.1使用throws声明抛出异常368 
10.4使用throw抛出异常370 
10.4.1抛出异常370 
10.4.2自定义异常类371 
10.4.3catch和throw同时使用372 
10.4.4Java7增强的throw语句373 
10.4.5异常链374 
10.5Java的异常跟踪栈376 
10.6异常处理规则377 
10.6.1不要过度使用异常378 
10.6.2不要使用过于庞大的try块379 
10.6.3避免使用CatchAll语句379 
10.6.4不要忽略捕获到的异常379 
10.7本章小结380 
本章练习380 
# 第11章 AWT编程381 
11.1GUI（图形用户界面）和AWT382 
11.2AWT容器383 
11.3布局管理器386 
11.3.1FlowLayout布局管理器386 
11.3.2BorderLayout布局管理器387 
BorderLayout最多只能放置5个组件吗？那它也太不实用了吧？388 
11.3.3GridLayout布局管理器389 
11.3.4GridBagLayout布局管理器390 
11.3.5CardLayout布局管理器392 
11.3.6绝对定位394 
11.3.7BoxLayout布局管理器395 
图11.15和图11.16显示的所有按钮都紧挨在一起，如果希望像FlowLayout、GridLayout等布局管理器那样指定组件的间距应该怎么办？396 
11.4AWT常用组件397 
11.4.1基本组件397 
11.4.2对话框（Dialog）399 
11.5事件处理401 
11.5.1Java事件模型的流程401 
11.5.2事件和事件监听器403 
11.5.3事件适配器407 
11.5.4使用内部类实现监听器408 
11.5.5使用外部类实现监听器408 
11.5.6类本身作为事件监听器类409 
11.5.7匿名内部类实现监听器410 
11.6AWT菜单410 
11.6.1菜单条、菜单和菜单项410 
11.6.2右键菜单412 
为什么即使我没有给多行文本域编写右键菜单，但当我在多行文本域上单击右键时也一样会弹出右键菜单？414 
11.7在AWT中绘图414 
11.7.1画图的实现原理414 
11.7.2使用Graphics类415 
11.8处理位图419 
11.8.1Image抽象类和BufferedImage 
实现类419 
11.8.2使用ImageIO输入／输出位图421 
11.9剪贴板425 
11.9.1数据传递的类和接口426 
11.9.2传递文本426 
11.9.3使用系统剪贴板传递图像428 
11.9.4使用本地剪贴板传递对象引用430 
11.9.5通过系统剪贴板传递Java对象433 
11.10拖放功能435 
11.10.1拖放目标436 
11.10.2拖放源439 
11.11本章小结440 
本章练习440 
# 第12章 Swing编程441 
12.1Swing概述442 
12.2Swing基本组件的用法443 
12.2.1Java7的Swing组件层次443 
12.2.2AWT组件的Swing实现444 
为什么单击Swing多行文本域时不是弹出像AWT多行文本域中的右键菜单？450 
12.2.3为组件设置边框450 
12.2.4Swing组件的双缓冲和键盘驱动452 
12.2.5使用JToolBar创建工具条453 
12.2.6使用JFileChooser和Java7增强 
的JColorChooser455 
12.2.7使用JOptionPane462 
12.3Swing中的特殊容器467 
12.3.1使用JSplitPane467 
12.3.2使用JTabbedPane469 
12.3.3使用JLayeredPane、JdesktopPane 
和JInternalFrame473 
12.4Swing简化的拖放功能480 
12.5Java7新增的Swing功能481 
12.5.1使用JLayer装饰组件481 
12.5.2创建透明、不规则形状窗口487 
12.6使用JProgressBar、ProgressMonitor 
和BoundedRangeModel创建进度条489 
12.6.1创建进度条489 
12.6.2创建进度对话框492 
12.7使用JSlider和BoundedRangeModel创建 
滑动条494 
12.8使用JSpinner和SpinnerModel创建微调控 
制器497 
12.9使用JList、JComboBox创建列表框500 
12.9.1简单列表框500 
12.9.2不强制存储列表项的ListModel和ComboBoxModel503 
12.9.3强制存储列表项的DefaultListModel 
和DefaultComboBoxModel506 
为什么JComboBox提供了添加、删除列表项的方法？而JList没有提供添加、删除列表项的方法呢？508 
12.9.4使用ListCellRenderer改变列表项 
外观508 
12.10使用JTree和TreeModel创建树510 
12.10.1创建树511 
12.10.2拖动、编辑树节点513 
12.10.3监听节点事件517 
12.10.4使用DefaultTreeCellRenderer改 
变节点外观519 
12.10.5扩展DefaultTreeCellRenderer改变 
节点外观520 
12.10.6实现TreeCellRenderer改变节点 
外观523 
12.11使用JTable和TableModel创建表格524 
12.11.1创建表格525 
我们指定的表格数据、表格列标题都是Object类型的数组，JTable如何显示这些Object对象？525 
12.11.2TableModel和监听器530 
12.11.3TableColumnModel和监听器534 
12.11.4实现排序537 
12.11.5绘制单元格内容540 
12.11.6编辑单元格内容543 
12.12使用JFormattedTextField和JtextPane 
创建格式文本546 
12.12.1监听Document的变化547 
12.12.2使用JPasswordField549 
12.12.3使用JFormattedTextField549 
12.12.4使用JEditorPane557 
12.12.5使用JTextPane557 
12.13本章小结564 
本章练习564 
# 第13章 MySQL数据库与JDBC编程565 
13.1JDBC基础566 
13.1.1JDBC简介566 
13.1.2JDBC驱动程序567 
13.2SQL语法568 
13.2.1安装数据库568 
13.2.2关系数据库基本概念和MySQL 
基本命令570 
13.2.3SQL语句基础572 
13.2.4DDL语句573 
13.2.5数据库约束577 
13.2.6索引584 
13.2.7视图585 
13.2.8DML语句语法585 
13.2.9单表查询588 
13.2.10数据库函数592 
13.2.11分组和组函数594 
13.2.12多表连接查询596 
13.2.13子查询599 
13.2.14集合运算601 
13.3JDBC的典型用法602 
13.3.1JDBC4.2常用接口和类简介602 
13.3.2JDBC编程步骤604 
前面给出的仅仅是MySQL和Oracle两种数据库的驱动，我看不出驱动类字符串有什么规律啊。如果我希望使用其他数据库，那怎么找到其他数据库的驱动类呢？604 
13.4执行SQL语句的方式607 
13.4.1使用Java8新增的 
executeLargeUpdate方法执行 
DDL和DML语句607 
13.4.2使用execute方法执行SQL语句608 
13.4.3使用PreparedStatement执行SQL 
语句610 
13.4.4使用CallableStatement调用存储 
过程614 
13.5管理结果集615 
13.5.1可滚动、可更新的结果集615 
13.5.2处理Blob类型数据617 
13.5.3使用ResultSetMetaData分析结 
果集622 
13.6Java7的RowSet1.1624 
13.6.1Java7新增的RowSetFactory与 
RowSet625 
13.6.2离线RowSet627 
13.6.3离线RowSet的查询分页629 
13.7事务处理630 
13.7.1事务的概念和MySQL事务支持630 
13.7.2JDBC的事务支持632 
13.7.3Java8增强的批量更新634 
13.8分析数据库信息635 
13.8.1使用DatabaseMetaData分析数据 
库信息635 
13.8.2使用系统表分析数据库信息636 
13.8.3选择合适的分析方式637 
13.9使用连接池管理连接638 
13.9.1DBCP数据源638 
13.9.2C3P0数据源639 
13.10本章小结640 
本章练习640 
# 第14章 Annotation（注释）641 
14.1基本Annotation642 
14.1.1限定重写父类方法：@Override642 
14.1.2标示已过时：@Deprecated643 
14.1.3抑制编译器警告： 
@SuppressWarnings644 
14.1.4Java7的“堆污染”警告与 
@SafeVarargs644 
14.1.5Java8的函数式接口与@FunctionalInterface645 
14.2JDK的元Annotation646 
14.2.1使用@Retention646 
14.2.2使用@Target647 
14.2.3使用@Documented647 
14.2.4使用@Inherited648 
14.3自定义Annotation649 
14.3.1定义Annotation649 
14.3.2提取Annotation信息650 
14.3.3使用Annotation的示例652 
14.3.4Java8新增的重复注解656 
14.3.5Java8新增的TypeAnnotation658 
14.4编译时处理Annotation659 
14.5本章小结663 
# 第15章 输入／输出664 
15.1File类665 
15.1.1访问文件和目录665 
15.1.2文件过滤器667 
15.2理解Java的IO流668 
15.2.1流的分类668 
15.2.2流的概念模型669 
15.3字节流和字符流670 
15.3.1InputStream和Reader670 
15.3.2OutputStream和Writer672 
15.4输入／输出流体系673 
15.4.1处理流的用法674 
15.4.2输入／输出流体系674 
15.4.3转换流677 
怎么没有把字符流转换成字节流的转换流呢？677 
15.4.4推回输入流678 
15.5重定向标准输入／输出679 
15.6Java虚拟机读写其他进程的数据680 
15.7RandomAccessFile682 
15.8对象序列化686 
15.8.1序列化的含义和意义686 
15.8.2使用对象流实现序列化686 
15.8.3对象引用的序列化688 
15.8.4自定义序列化692 
15.8.5另一种自定义序列化机制696 
15.8.6版本698 
15.9NIO699 
15.9.1Java新IO概述699 
15.9.2使用Buffer699 
15.9.3使用Channel702 
15.9.4字符集和Charset705 
二进制序列与字符之间如何对应呢？706 
15.9.5文件锁707 
15.10Java7的NIO.2709 
15.10.1Path、Paths和Files核心API709 
15.10.2使用FileVisitor遍历文件和目录710 
15.10.3使用WatchService监控文件变化711 
15.10.4访问文件属性712 
15.11本章小结714 
本章练习714 
# 第16章 多线程715 
16.1线程概述716 
16.1.1线程和进程716 
16.1.2多线程的优势717 
16.2线程的创建和启动718 
16.2.1继承Thread类创建线程类718 
16.2.2实现Runnable接口创建线程类719 
16.2.3使用Callable和Future创建线程720 
16.2.4创建线程的三种方式对比722 
16.3线程的生命周期722 
16.3.1新建和就绪状态722 
16.3.2运行和阻塞状态724 
16.3.3线程死亡725 
16.4控制线程726 
16.4.1join线程726 
16.4.2后台线程727 
16.4.3线程睡眠：sleep728 
16.4.4线程让步：yield729 
16.4.5改变线程优先级730 
16.5线程同步731 
16.5.1线程安全问题731 
16.5.2同步代码块733 
16.5.3同步方法735 
16.5.4释放同步监视器的锁定737 
16.5.5同步锁（Lock）737 
16.5.6死锁739 
16.6线程通信741 
16.6.1传统的线程通信741 
16.6.2使用Condition控制线程通信744 
16.6.3使用阻塞队列（BlockingQueue） 
控制线程通信746 
16.7线程组和未处理的异常749 
16.8线程池752 
16.8.1Java8改进的线程池752 
16.8.2Java8增强的ForkJoinPool754 
16.9线程相关类757 
16.9.1ThreadLocal类757 
16.9.2包装线程不安全的集合759 
16.9.3线程安全的集合类759 
16.10本章小结760 
# 第17章 网络编程761 
17.1网络编程的基础知识762 
17.1.1网络基础知识762 
17.1.2IP地址和端口号763 
17.2Java的基本网络支持764 
17.2.1使用InetAddress764 
17.2.2使用URLDecoder和 
URLEncoder765 
17.2.3URL、URLConnection和 
URLPermission766 
17.3基于TCP协议的网络编程772 
17.3.1TCP协议基础772 
17.3.2使用ServerSocket创建TCP 
服务器端773 
17.3.3使用Socket进行通信773 
17.3.4加入多线程776 
17.3.5记录用户信息778 
17.3.6半关闭的Socket785 
17.3.7使用NIO实现非阻塞Socket通信786 
17.3.8使用Java7的AIO实现非阻塞 
通信792 
上面程序中好像没用到④⑤号代码的get（）方法的返回值，这两个地方不调用get（）方法行吗？795 

17.4基于UDP协议的网络编程798 
17.4.1UDP协议基础799 
17.4.2使用DatagramSocket发送、接收 
数据799 
17.4.3使用MulticastSocket实现多点广播803 
17.5使用代理服务器813 
17.5.1直接使用Proxy创建连接813 
17.5.2使用ProxySelector自动选择代理 
服务器814 
17.6本章小结817 
本章练习817 
# 第18章 类加载机制与反射818 
18.1类的加载、连接和初始化819 
18.1.1JVM和类819 
18.1.2类的加载820 
18.1.3类的连接821 
18.1.4类的初始化821 
18.1.5类初始化的时机822 
18.2类加载器823 
18.2.1类加载器简介823 
18.2.2类加载机制824 
18.2.3创建并使用自定义的类加载器826 
18.2.4URLClassLoader类829 
18.3通过反射查看类信息830 
18.3.1获得Class对象830 
18.3.2从Class中获取信息831 
18.3.3Java8新增的方法参数反射835 
18.4使用反射生成并操作对象836 
18.4.1创建对象836 
18.4.2调用方法838 
18.4.3访问成员变量值840 
18.4.4操作数组841 
18.5使用反射生成JDK动态代理842 
18.5.1使用Proxy和InvocationHandler 
创建动态代理843 
18.5.2动态代理和AOP844 
18.6反射和泛型848 
18.6.1泛型和Class类848 
18.6.2使用反射来获取泛型信息850 
18.7本章小结851 
本章练习851




# 附录:

