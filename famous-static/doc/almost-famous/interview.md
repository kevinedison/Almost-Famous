

#### 集合框架有哪些？

```
1、List

1.1、ArrayList
1.2、LinkedList
1.3、Vector
1.4、List接口下各种接口实现类的比较和应用

2、Set

2.1、HashSet
2.2、TreeSet
2.3、SortSet
2.4、LinkedHashSet
2.5、Set接口下的各种接口实现类的比较和应用

3、Map

3.1、HashMap
3.2、LinkedHashMap
3.3、TreeMap
3.4、WeakHashMap
3.5、SortedMap
3.6、Map接口下的各种接口实现类的比较和应用

4、Collections
4、Arrays
```
#### List,LinkedList,ArrayList使用场景，特点？

```
List 是一个接口，它继承于Collection的接口。它代表着有序的队列。
ArrayList, LinkedList是List的2个实现类
ArrayList 是一个数组队列，相当于动态数组。它由数组实现，随机访问效率高，随机插入、随机删除效率低。
LinkedList 是一个双向链表。它也可以被当作堆栈、队列或双端队列进行操作。LinkedList随机访问效率低，但随机插入、随机删除效率低。
```
#### HashMap为什么是不安全的？

> https://www.jianshu.com/p/e2f75c8cce01
```
HashMap会进行resize操作，在resize操作的时候会造成线程不安全。
1、put的时候导致的多线程数据不一致。
2、另外一个比较明显的线程不安全的问题是HashMap的get操作可能因为resize而引起死循环（cpu100%）
```
#### 微服务优点，为什么要用微服务？

> http://www.uml.org.cn/wfw/201806064.asp?artid=20818?weiid=2164
```
微服务架构：将单体应用拆分为多个高内聚低耦合的小型服务，每个小服务运行在独立进程，由不同的团队开发和维护，服务间采用轻量级通信机制，独立自动部署，可以采用不同的语言及存储。
```
#### 怎么理解多态？

> https://www.cnblogs.com/hupp/p/4854918.html
```
什么是多态

面向对象的三大特性：封装、继承、多态。从一定角度来看，封装和继承几乎都是为多态而准备的。这是我们最后一个概念，也是最重要的知识点。
多态的定义：指允许不同类的对象对同一消息做出响应。即同一消息可以根据发送对象的不同而采用多种不同的行为方式。（发送消息就是函数调用）
实现多态的技术称为：动态绑定（dynamic binding），是指在执行期间判断所引用对象的实际类型，根据其实际的类型调用其相应的方法。
多态的作用：消除类型之间的耦合关系。
现实中，关于多态的例子不胜枚举。比方说按下 F1 键这个动作，如果当前在 Flash 界面下弹出的就是 AS 3 的帮助文档；如果当前在 Word 下弹出的就是 Word 帮助；在 Windows 下弹出的就是 Windows 帮助和支持。同一个事件发生在不同的对象上会产生不同的结果。
下面是多态存在的三个必要条件，要求大家做梦时都能背出来！

多态存在的三个必要条件 一、要有继承； 二、要有重写； 三、父类引用指向子类对象。

```
#### 你了解什么设计模式？可以说一下你是怎么使用为什么要用工厂模式吗？对简单工厂，动态工厂，抽象工厂有什么认识？

```

```
#### Spring的核心内容是什么？你怎么理解IOC，AOP它的使用和场景？

```
IOC容器(控制反转、依赖注入)，AOP(切面编程、动态代理)

```
#### 线程的状态有那些？暂停线程方式，创建线程方式？

```
1.新建状态(New)
2.就绪状态(Runnable)
3.运行状态（Running）
4.阻塞状态（Blocked）
5.死亡状态（Dead）
```
#### 你对微服务限流的理解？

```

```
#### 你了解类加载在jvm中流程机制吗？

```

```
#### 你项目中为什么不用websocket做消息盒子？使用客户端定时请求，服务端可以挂多少客户端？

```

```
#### 你对netty的认识？什么是多路复用？

```

```
#### post与get请求区别？为什么不用get提交数据？Servlet如何识别post,get请求？get提交数据有大小限制吗？大概是多少？post表单提交，数据如何封装，有大小限制吗？

```

```
#### mybatis和hibernate区别,使用场景有什么区别？你如何去保障注入安全的？

```

```