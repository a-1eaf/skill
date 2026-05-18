MyBatis面试题

1. 什么是Mybatis?
2. Mybaits的优点
3. MyBatis框架的缺点
4. MyBatis框架适用场合
5. MyBatis与Hibernate有哪些不同?
6. #{}和${}的区别是什么?
7. 当实体类中的属性名和表中的字段名不一样,怎么办?
8. 模糊查询like语句该怎么写?
9. 通常一个Xml映射文件，都会写一个Dao接口与之对应，请问，这个Dao接口的工作原理是什么?Dao接口里的方法，参数不同时，方法能重载吗?
10. Mybatis是如何进行分页的?分页插件的原理是什么?
11. Mybatis是如何将sql执行结果封装为目标对象并返回的?都有哪些映射形式?
12. 如何执行批量插入?
13. 如何获取自动生成的(主)键值?
14. 在mapper中如何传递多个参数?
15. Mybatis动态sql有什么用?执行原理?有哪些动态sql?
16. Xml映射文件中，除了常见的selectinsert updae delete标签之外，还有哪些标签?
17. Mybatis的Xml映射文件中，不同的Xml映射文件，id是否可以重复?
18. 为什么说Mybatis是半自动ORM映射工具?它与全自动的区别在哪里?
19. 一对一、一对多的关联查询?
20. MyBatis实现一对一有几种方式?具体怎么操作的?
21. MyBatis实现一对多有几种方式,怎么操作的?
22. Mybatis是否支持延迟加载?如果支持，它的实现原理是什么?
23. Mybatis的一级、二级缓存
24. 什么是MyBatis的接口绑定?有哪些实现方式?
25. 使用MyBatis的mapper接口调用时有哪些要求?
26. Mapper编写有哪几种方式?
27. 简述Mybatis的插件运行原理,以及如何编写一个插件。

ZooKeeper面试题

1. ZooKeeper面试题?
2. ZooKeeper提供了什么?
3. Zookeeper文件系统
4. ZAB协议?
5. 四种类型的数据节点Znode
6. Zookeeper Watcher机制--数据变更通知
7. 客户端注册Watcher实现
8. 服务端处理Watcher实现
9. 客户端回调Watcher
10. ACL权限控制机制
11. Chroot特性
12. 会话管理
13. 服务器角色
14. Zookeeper下Server工作状态
15. 数据同步
16. zookeeper是如何保证事务的顺序一致性的?
17. 分布式集群中为什么会有Master?
18. zk节点宕机如何处理?
19. zookeeper负载均衡和nginx负载均衡区别
20. Zookeeper有哪几种几种部署模式?
21. 集群最少要几台机器，集群规则是怎样的?
22. 集群支持动态添加机器吗?
23. Zookeeper对节点的watch监听通知是永久的吗?为什么不是永久的?
24. Zookeeper的java客户端都有哪些?
25. chubby是什么，和zookeeper比你怎么看?
26. 说几个zookeeper常用的命令。
27. ZAB和Paxos算法的联系与区别?
28. Zookeeper的典型应用场景

Dubbo面试题

1. 为什么要用Dubbo?
2. Dubbo的整体架构设计有哪些分层?
3. 默认使用的是什么通信框架，还有别的选择吗?
4. 服务调用是阻塞的吗?
5. 一般使用什么注册中心?还有别的选择吗?
6. 默认使用什么序列化框架，你知道的还有哪些?
7. 服务提供者能实现失效踢出是什么原理?
8. 服务上线怎么不影响旧版本?
9. 如何解决服务调用链过长的问题?
10. 说说核心的配置有哪些?
11. Dubbo推荐用什么协议?
12. 同一个服务多个注册的情况下可以直连某一个服务吗?
13. 画一画服务注册与发现的流程图
14. Dubbo集群容错有几种方案?
15. Dubbo服务降级，失败重试怎么做?
16. Dubbo使用过程中都遇到了些什么问题?
17. Dubbo Monitor实现原理?
18. Dubbo用到哪些设计模式?
19. Dubbo配置文件是如何加载到Spring中的?
20. Dubbo SPI和Java SPI区别?
21. Dubbo支持分布式事务吗?
22. Dubbo可以对结果进行缓存吗?
23. 服务上线怎么兼容旧版本?
24. Dubbo必须依赖的包有哪些?
25. Dubbo telnet命令能做什么?
26. Dubbo支持服务降级吗?
27. Dubbo如何优雅停机?
28. Dubbo和Dubbox之间的区别?
29. Dubbo和Spring Cloud的区别?
30. 你还了解别的分布式框架吗?

Elasticsearch面试题

1. elasticsearch了解多少,说说你们公司es的集群架构,索引数据大小，分片有多少，以及一些调优手段。
2. elasticsearch的倒排索引是什么
3. elasticsearch索引数据多了怎么办,如何调优,部署
4. elasticsearch是如何实现master选举的
5. 详细描述一下Elasticsearch索引文档的过程
6. 详细描述一下Elasticsearch搜索的过程?
7. Elasticsearch在部署时，对Linux的设置有哪些优化方法
8. lucence内部结构是什么?
9. Elasticsearch是如何实现Master选举的?
10. Elasticsearch中的节点(比如共20个)，其中的10个选了一个master，另外10个选了另一个master，怎么办?
11. 客户端在和集群连接时，如何选择特定的节点执行请求的?
12. 详细描述一下Elasticsearch索引文档的过程。
13. 详细描述一下Elasticsearch更新和删除文档的过程。
14. 详细描述一下Elasticsearch搜索的过程。
15. 在Elasticsearch中，是怎么根据一个词找到对应的倒排索引的?
16. Elasticsearch在部署时，对Linux的设置有哪些优化方法?
17. 对于GC方面,在使用Elasticsearch时要注意什么?
18. Elasticsearch对于大数据量(上亿量级)的聚合如何实现?
19. 在并发情况下, Elasticsearch如果保证读写一致?
20. 如何监控Elasticsearch集群状态?
21. 介绍下你们电商搜索的整体技术架构。
22. 介绍一下你们的个性化搜索方案?
23. 是否了解字典树?
24. 拼写纠错是如何实现的?

Memcached面试题

1. Memcached是什么，有什么作用?
2. Memcached服务分布式集群如何实现?
3. Memcached服务特点及工作原理是什么?
4. 简述Memcached内存管理机制原理?
5. memcached是怎么工作的?
6. memcached最大的优势是什么?
7. memcached和MySQL的query
8. memcached和服务器的local cache(比如PHP的APC、mmap文件等)相比，有什么优缺点?
9. memcached的cache机制是怎样的?
10. memcached如何实现冗余机制?
11. memcached如何处理容错的?
12. 如何将memcached中item批量导入导出?
13. 如果缓存数据在导出导入之间过期了，您又怎么处理这些数据呢?
14. memcached是如何做身份验证的?
15. memcached的多线程是什么?如何使用它们?
16. memcached能接受的key的最大长度是多少?
17. memcached最大能存储多大的单个item?
18. memcached能够更有效地使用内存吗?
19. 什么是二进制协议，我该关注吗?
20. memcached的内存分配器是如何工作的?为什么不适用malloc/free?为何要使用slabs?
21. memcached是原子的吗?
22. 如何实现集群中的session共享存储?
23. memcached与redis的区别?

Redis面试题

1. 什么是Redis?
2. Redis的数据类型?
3. 使用Redis有哪些好处?
4. Redis相比Memcached有哪些优势?
5. Memcache与Redis的区别都有哪些?
6. Redis是单进程单线程的?
7. 一个字符串类型的值能存储最大容量是多少?
8. Redis的持久化机制是什么?各自的优缺点?
9. Redis常见性能问题和解决方案
10. redis过期键的删除策略?
11. Redis的回收策略(淘汰策略)?
12. 为什么edis需要把所有数据放到内存中?
13. Redis的同步机制了解么?
14. Pipeline有什么好处，为什么要用pipeline?
15. 是否使用过Redis集群，集群的原理是什么?
16. Redis集群方案什么情况下会导致整个集群不可用?
17. Redis支持的Java客户端都有哪些?官方推荐用哪个?
18. Jedis与Redisson对比有什么优缺点?
19. Redis如何设置密码及验证密码?
20. 说说Redis哈希槽的概念?
21. Redis集群的主从复制模型是怎样的?
22. Redis集群会有写操作丢失吗?为什么?
23. Redis集群之间是如何复制的?
24. Redis集群最大节点个数是多少?
25. Redis集群如何选择数据库?
26. 怎么测试Redis的连通性?
27. 怎么理解Redis事务?
28. Redis事务相关的命令有哪几个?
29. Redis key的过期时间和永久有效分别怎么设置?
30. Redis如何做内存优化?
31. Redis回收进程如何工作的?
32. 都有哪些办法可以降低Redis的内存使用情况呢?
33. Redis的内存用完了会发生什么?
34. 一个Redis实例最多能存放多少的keys?List、Set、Sorted Set他们最多能存放多少元素?
35. MySQL里有2000w数据，redis中只存20w的数据，如何保证redis中的数据都是热点数据?
36. Redis最适合的场景?
37. 假如Redis里面有1亿个key，其中有10w个key是以某个固定的已知的前缀开头的，如果将它们全部找出来?
38. 如果有大量的key需要设置同一时间过期，一般需要注意什么?
39. 使用过Redis做异步队列么，你是怎么用的?
40. 使用过Redis分布式锁么，它是什么回事?

MySQL面试题

1. MySQL中有哪几种锁?
2. MySQL中有哪些不同的表格?
3. 简述在MySQL数据库中MyISAM和InnoDB的区别
4. MySQL中InnoDB支持的四种事务隔离级别名称，以及逐级之间的区别?
5. CHAR和VARCHAR的区别?
6. 主键和候选键有什么区别?
7. myisamchk是用来做什么的?
8. 如果一个表有一列定义为TIMESTAMP,将发生什么?
9. 你怎么看到为表格定义的所有索引?
10. LIKE声明中的%和_是什么意思?
11. 列对比运算符是什么?
12. BLOB和TEXT有什么区别?
13. MySQL_fetch_array和MySQL_fetch_object的区别是什么?
14. MyISAM表格将在哪里存储,并且还提供其存储格式?
15. MySQL如何优化DISTINCT?
16. 如何显示前50行?
17. 可以使用多少列创建索引?
18. NOW()和CURRENT_DATE()有什么区别?
19. 什么是非标准字符串类型?
20. 什么是通用SQL函数?
21. MySQL支持事务吗?
22. MySQL里记录货币用什么字段类型好
23. MySQL有关权限的表都有哪几个?
24. 列的字符串类型可以是什么?
25. MySQL数据库作发布系统的存储,一天五万条以上的增量,预计运维三年,怎么优化?
26. 锁的优化策略
27. 索引的底层实现原理和优化
28. 什么情况下设置了索引但无法使用
29. 实践中如何优化MySQL
30. 优化数据库的方法
31. 简单描述MySQL中，索引，主键，唯一索引，联合索引的区别，对数据库的性能有什么影响(从读写两方面)
32. 数据库中的事务是什么?
33. SQL注入漏洞产生的原因?如何防止?
34. 为表中得字段选择合适得数据类型
35. 存储时期
36. 对于关系型数据库而言，索引是相当重要的概念，请回答有关索引的几个问题
37. 解释MySQL外连接、内连接与自连接的区别
38. Myql中的事务回滚机制概述
39. SQL语言包括哪几部分?每部分都有哪些操作关键字?
40. 完整性约束包括哪些?
41. 什么是锁?
42. 什么叫视图?游标是什么?
43. 什么是存储过程?用什么来调用?
44. 如何通俗地理解三个范式?
45. 什么是基本表?什么是视图?
46. 试述视图的优点?
47. NULL是什么意思
48. 主键、外键和索引的区别?
49. 你可以用什么来确保表格里的字段只接受特定范围里的值?
50. 说说对SQL语句优化有哪些方法?(选择几条)

Java并发编程(一)

1. 在java中守护线程和本地线程区别?
2. 线程与进程的区别?
3. 什么是多线程中的上下文切换?
4. 死锁与活锁的区别,死锁与饥饿的区别?
5. Java中用到的线程调度算法是什么?
6. 什么是线程组，为什么在Java中不推荐使用?
7. 为什么使用Executor框架?
8. 在Java中Executor和Executors的区别?
9. 如何在Windows和Linux上查找哪个线程使用的CPU时间最长?
10. 什么是原子操作?在Java Concurrency API中有哪些原子类(atomic classes)?
11. Java Concurrency API中的Lock接口(Lock interface)是什么?对比同步它有什么优势?
12. 什么是Executors框架?
13. 什么是阻塞队列?阻塞队列的实现原理是什么?如何使用阻塞队列来实现生产者-消费者模型?
14. 什么是Callable和Future?
15. 什么是FutureTask?使用ExecutorService启动任务。
16. 什么是并发容器的实现?
17. 多线程同步和互斥有几种实现方法，都是什么?
18. 什么是竞争条件?你怎样发现和解决竞争?
19. 你将如何使用thread dump?你将如何分析Thread dump?
20. 为什么我们调用start()方法时会执行run()方法，为什么我们不能直接调用run()方法?
21. Java中你怎样唤醒一个阻塞的线程?
22. 在Java中CycliBarriar和CountdownLatch有什么区别?
23. 什么是不可变对象，它对写并发应用有什么帮助?
24. 什么是多线程中的上下文切换?
25. Java中用到的线程调度算法是什么?
26. 什么是线程组，为什么在Java中不推荐使用?
27. 为什么使用Executor框架比使用应用创建和管理线程好?
28. java中有几种方法可以实现一个线程?
29. 如何停止一个正在运行的线程?
30. notify()和notifyAll()有什么区别?
31. 什么是Daemon线程?它有什么意义?
32. java如何实现多线程之间的通讯和协作?
33. 什么是可重入锁(ReentrantLock)?
34. 当一个线程进入某个对象的一个synchronized的实例方法后，其它线程是否可进入此对象的其它方法?
35. 乐观锁和悲观锁的理解及如何实现，有哪些实现方式?
36. SynchronizedMap和ConcurrentHashMap有什么区别?
37. CopyOnWriteArrayList可以用于什么应用场景?
38. 什么叫线程安全?servlet是线程安全吗?
39. volatile有什么用?能否用一句话说明下volatile的应用场景?
40. 为什么代码会重排序?
41. 在java中wait和sleep方法的不同?
42. 用Java实现阻塞队列
43. 一个线程运行时发生异常会怎样?
44. 如何在两个线程间共享数据?
45. Java中notify和notifyAll有什么区别?
46. 为什么wait,notify和notifyAll这些方法不在thread类里面?
47. 什么是ThreadLocal变量?
48. Java中interrupted和isInterrupted方法的区别?
49. 为什么wait和notify方法要在同步块中调用?
50. 为什么你应该在循环中检查等待条件?
51. Java中的同步集合与并发集合有什么区别?
52. 什么是线程池?为什么要使用它?
53. 怎么检测一个线程是否拥有锁?
54. 你如何在Java中获取线程堆栈?
55. 线程类中的yield方法有什么作用?
56. Java中ConcurrentHashMap的并发度是什么?
57. Java中Semaphore是什么?
58. Java线程池中submit()和execute()方法有什么区别?
59. 什么是阻塞式方法?
60. Java中的ReadWriteLock是什么?
61. volatile变量和atomic变量有什么不同?
62. 可以直接调用Thread类的run()方法么?
63. 如何让正在运行的线程暂停一段时间?
64. 你对线程优先级的理解是什么?
65. 什么是线程调度器(Thread Scheduler)和时间分片(Time Slicing)?
66. 你如何确保main()方法所在的线程是Java程序最后结束的线程?
67. 线程之间是如何通信的?
68. 为什么线程通信的方法wait(),notify()和notifyAll()被定义在Object类里?
69. 为什么wait(),notify()和notifyAll()必须在同步方法或者同步块中被调用?
70. 为什么Thread类的sleep()和yield()方法是静态的?
71. 如何确保线程安全?
72. 同步方法和同步块，哪个是更好的选择?
73. 如何创建守护线程?
74. 什么是Java Timer类?如何创建一个有特定时间间隔的任务?

Java并发编程(二)

1. 并发编程三要素?
2. 实现可见性的方法有哪些?
3. 多线程的价值?
4. 创建线程的有哪些方式?
5. 创建线程的三种方式的对比?
6. 线程的状态流转图
7. Java线程具有五中基本状态
8. 什么是线程池?有哪几种创建方式?
9. 四种线程池的创建
10. 线程池的优点?
11. 常用的并发工具类有哪些?
12. CyclicBarrier和CountDownLatch的区别
13. synchronized的作用?
14. volatile关键字的作用
15. 什么是CAS
16. CAS的问题
17. 什么是Future?
18. 什么是AQS
19. AQS支持两种同步方式
20. ReadWriteLock是什么
21. FutureTask是什么
22. synchronized和ReentrantLock的区别
23. 什么是乐观锁和悲观锁
24. 线程B怎么知道线程A修改了变量
25. synchronized、volatile、CAS比较
26. sleep方法和wait方法有什么区别?
27. ThreadLocal是什么?有什么用?
28. 为什么wait()方法和notify()/notifyAll()方法要在同步块中被调用
29. 多线程同步有哪几种方法?
30. 线程的调度策略
31. ConcurrentHashMap的并发度是什么
32. Linux环境下如何查找哪个线程使用CPU最长
33. Java死锁以及如何避免?
34. 死锁的原因
35. 怎么唤醒一个阻塞的线程
36. 不可变对象对多线程有什么帮助
37. 什么是多线程的上下文切换
38. 如果你提交任务时,线程池队列已满,这时会发生什么
39. Java中用到的线程调度算法是什么
40. 什么是线程调度器(Thread Scheduler)和时间分片(Time Slicing)?
41. 什么是自旋
42. Java Concurrency API中的Lock接口(Lock interface)是什么?对比同步它有什么优势?
43. 单例模式的线程安全性
44. Semaphore有什么作用
45. Executors类是什么?
46. 线程类的构造方法、静态块是被哪个线程调用的
47. 同步方法和同步块,哪个是更好的选择?
48. Java线程数过多会造成什么异常?

Java面试题(一)

1. 面向对象的特征有哪些方面?
2. 访问修饰符public,private,protected,以及不写(默认)时的区别?
3. String是最基本的数据类型吗?
4. float f=3.4;是否正确?
5. short s1=1; s1= s1+1;有错吗?short s1=1; s1+= 1;有错吗?
6. Java有没有goto?
7. int和Integer有什么区别?
8. &和&&的区别?
9. 解释内存中的栈(stack)、堆(heap)和方法区(method area)的用法。
10. Math.round(11.5)等于多少?Math.round(-11.5)等于多少?
11. switch是否能作用在byte上,是否能作用在long上,是否能作用在String上?
12. 用最有效率的方法计算2乘以8?
13. 数组有没有length()方法?String有没有length()方法?
14. 在Java中，如何跳出当前的多重嵌套循环?
15. 构造器(constructor)是否可被重写(override)?
16. 两个对象值相同(x.equals(y)==true),但却可有不同的hash code,这句话对不对?
17. 是否可以继承String类?
18. 当一个对象被当作参数传递到一个方法后，此方法可改变这个对象的属性,并可返回变化后的结果,那么这里到底是值传递还是引用传递?
19. String和StringBuilder、StringBuffer的区别?
20. 重载(Overload)和重写(Override)的区别。重载的方法能否根据返回类型进行区分?
21. 描述一下JVM加载class文件的原理机制?
22. char型变量中能不能存贮一个中文汉字,为什么?
23. 抽象类(abstract class)和接口(interface)有什么异同?
24. 静态嵌套类(Static Nested Class)和内部类(Inner Class)的不同?
25. Java中会存在内存泄漏吗,请简单描述。
26. 抽象的(abstract)方法是否可同时是静态的(static),是否可同时是本地方法(native),是否可同时被synchronized修饰?
27. 阐述静态变量和实例变量的区别。
28. 是否可以从一个静态(static)方法内部发出对非静态(non-static)方法的调用?
29. 如何实现对象克隆?
30. GC是什么?为什么要有GC?
31. String s=new String("xyz");创建了几个字符串对象?
32. 接口是否可继承(extends)接口?抽象类是否可实现(implements)接口?抽象类是否可继承具体类(concrete class)?
33. 一个".java"源文件中是否可以包含多个类(不是内部类)?有什么限制?
34. Anonymous Inner Class(匿名内部类)是否可以继承其它类?是否可以实现接口?
35. 内部类可以引用它的包含类(外部类)的成员吗?有没有什么限制?
36. Java中的final关键字有哪些用法?
37. 指出下面程序的运行结果
38. 数据类型之间的转换
39. 如何实现字符串的反转及替换?
40. 怎样将GB2312编码的字符串转换为ISO-8859-1编码的字符串?
41. 日期和时间
42. 打印昨天的当前时刻。
43. 比较一下Java和JavaScript。
44. 什么时候用断言(assert)?
45. Error和Exception有什么区别?
46. try{}里有一个return语句，那么紧跟在这个try后的finally{}里的代码会不会被执行，什么时候被执行，在return前还是后?
47. Java语言如何进行异常处理，关键字:throws、throw、try、catch、finally分别如何使用?
48. 运行时异常与受检异常有何异同?
49. 列出一些你常见的运行时异常?
50. 阐述final、finally、finalize的区别。
51. 类ExampleA继承Exception，类ExampleB继承ExampleA。
52. List、Set、Map是否继承自Collection接口?
53. 阐述ArrayList、Vector、LinkedList的存储性能和特性。
54. Collection和Collections的区别?
55. List、Map、Set三个接口存取元素时，各有什么特点?
56. TreeMap和TreeSet在排序时如何比较元素?Collections工具类中的sort()方法如何比较元素?
57. Thread类的sleep()方法和对象的wait()方法都可以让线程暂停执行，它们有什么区别?
58. 线程的sleep()方法和yield()方法有什么区别?
59. 当一个线程进入一个对象的synchronized方法A之后，其它线程是否可进入此对象的synchronized方法B?
60. 请说出与线程同步以及线程调度相关的方法。
61. 编写多线程程序有几种实现方式?
62. synchronized关键字的用法?
63. 举例说明同步和异步。
64. 启动一个线程是调用run()还是start()方法?
65. 什么是线程池(thread pool)?
66. 线程的基本状态以及状态之间的关系?
67. 简述synchronized和java.util.concurrent.locks.Lock的异同?
68. Java中如何实现序列化,有什么意义?
69. Java中有几种类型的流?
70. 写一个方法，输入一个文件名和一个字符串，统计这个字符串在这个文件中出现的次数。
71. 如何用Java代码列出一个目录下所有的文件?
72. 用Java的套接字编程实现一个多线程的回显(echo)服务器。
73. XML文档定义有几种形式?它们之间有何本质区别?解析XML文档有哪几种方式?
74. 你在项目中哪些地方用到了XML?
75. 阐述JDBC操作数据库的步骤。
76. Statement和PreparedStatement有什么区别?哪个性能更好?
77. 使用JDBC操作数据库时，如何提升读取数据的性能?如何提升更新数据的性能?
78. 在进行数据库编程时，连接池有什么作用?
79. 什么是DAO模式?
80. 事务的ACID是指什么?
81. 说一下mysql数据库存储的原理
82. JDBC能否处理Blob和Clob?
83. 简述正则表达式及其用途。
84. Java中是如何支持正则表达式操作的?
85. 获得一个类的类对象有哪些方式?
86. 如何通过反射创建对象?
87. 如何通过反射调用对象的方法?
88. 简述一下你了解的设计模式。
89. 用Java写一个单例类。
90. 什么是UML?
91. UML中有哪些常用的图?
92. 什么是Java序列化,如何实现Java序列化?
93. 用Java写一个折半查找。

Java面试题(二)

1. Java中能创建volatile数组吗?
2. volatile能使得一个非原子操作变成原子操作吗?
3. volatile修饰符的有过什么实践?
4. volatile类型变量提供什么保证?
5. 10个线程和2个线程的同步代码,哪个更容易写?
6. 你是如何调用wait()方法的?使用if块还是循环?为什么?
7. 什么是多线程环境下的伪共享(false sharing)?
8. 什么是Busy spin?我们为什么要使用它?
9. Java中怎么获取一份线程dump文件?
10. Swing是线程安全的?
11. 什么是线程局部变量?
12. 用wait-notify写一段代码来解决生产者-消费者问题?
13. 用Java写一个线程安全的单例模式(Singleton)?
14. Java中sleep方法和wait方法的区别?
15. 什么是不可变对象(immutable object)?Java中怎么创建一个不可变对象?
16. 我们能创建一个包含可变对象的不可变对象吗?
17. Java中应该使用什么数据类型来代表价格?
18. 怎么将byte转换为String?
19. Java中怎样将bytes转换为long类型?
20. 我们能将int强制转换为byte类型的变量吗?如果该值大于byte类型的范围,将会出现什么现象?
21. 存在两个类,B继承A,C继承B,我们能将B转换为C么?如C=(C)B;
22. 哪个类包含clone方法?是Cloneable还是Object?
23. Java中++操作符是线程安全的吗?
24. a=a+b与a+=b的区别
25. 我能在不进行强制转换的情况下将一个double值赋值给long类型的变量吗?
26. 3*0.1==0.3将会返回什么?true还是false?
27. int和Integer哪个会占用更多的内存?
28. 为什么Java中的String是不可变的(Immutable)?
29. 谈谈final、finally、finalize的区别
30. 谈谈2的补码
31. 64位JVM中，int的长度是多数?
32. Serial与Parallel GC之间的不同之处?
33. 32位和64位的JVM，int类型变量的长度是多数?
34. Java中WeakReference与SoftReference的区别?
35. WeakHashMap是怎么工作的?
36. JVM选项-XX:+UseCompressedOops有什么作用?为什么要使用?
37. 怎样通过Java程序来判断JVM是32位还是64位?
38. 32位JVM和64位JVM的最大堆内存分别是多数?
39. JRE、JDK、JVM及JIT之间有什么不同?
40. 解释Java堆空间及GC?
41. 你能保证GC执行吗?
42. 怎么获取Java程序使用的内存?堆使用的百分比?
43. Java中堆和栈有什么区别?
44. "a==b"和"a.equals(b)"有什么区别?
45. a.hashCode()有什么用?与a.equals(b)有什么关系?
46. final、finalize和finally的不同之处?
47. Java中的编译期常量是什么?使用它又什么风险?
48. List、Set、Map和Queue之间的区别(答案)
49. poll()方法和remove()方法的区别?
50. Java中LinkedHashMap和PriorityQueue的区别是什么?
51. ArrayList与LinkedList的不区别?
52. 用哪两种方式来实现集合的排序?
53. Java中怎么打印数组?
54. Java中的LinkedList是单向链表还是双向链表?
55. Java中的TreeMap是采用什么树实现的?(答案)
56. Hashtable与HashMap有什么不同之处?
57. Java中的HashSet，内部是如何工作的?
58. 写一段代码在遍历ArrayList时移除一个元素?
59. 我们能自己写一个容器类，然后使用for-each循环码?
60. ArrayList和HashMap的默认大小是多数?
61. 有没有可能两个不相等的对象有有相同的hashcode?
62. 两个相同的对象会有不同的的hash code吗?
63. 我们可以在hashcode()中使用随机数字吗?
64. Java中，Comparator与Comparable有什么不同?
65. Java中怎么创建ByteBuffer?
66. Java中，怎么读写ByteBuffer?
67. Java采用的是大端还是小端?
68. ByteBuffer中的字节序是什么?
69. Java中，直接缓冲区与非直接缓冲器有什么区别?
70. Java中的内存映射缓存区是什么?
71. socket选项TCP NO DELAY是指什么?
72. TCP协议与UDP协议有什么区别?
73. Java中，ByteBuffer与StringBuffer有什么区别?
74. Java中，编写多线程程序的时候你会遵循哪些最佳实践?
75. 说出几点Java中使用Collections的最佳实践
76. 说出至少5点在Java中使用线程的最佳实践。
77. 说出5条IO的最佳实践
78. 列出5个应该遵循的JDBC最佳实践
79. 说出几条Java中方法重载的最佳实践?
80. 在多线程环境下，SimpleDateFormat是线程安全的吗?
81. Java中如何格式化一个日期?如格式化为ddMMyyyy的形式?
82. Java中，怎么在格式化的日期中显示时区?
83. Java中java.util.Date与java.sql.Date有什么区别?
84. Java中，如何计算两个日期之间的差距?
85. Java中，如何将字符串YYYYMMDD转换为日期?
86. 如何测试静态方法?(答案)
87. 怎么利用JUnit来测试一个方法的异常?
88. 你使用过哪个单元测试库来测试你的Java程序?
89. @Before和@BeforeClass有什么区别?
90. 怎么检查一个字符串只包含数字?解决方案
91. Java中如何利用泛型写一个LRU缓存?
92. 写一段Java程序将byte转换为long?
93. 在不使用StringBuffer的前提下,怎么反转一个字符串?
94. Java中，怎么获取一个文件中单词出现的最高频率?
95. 如何检查出两个给定的字符串是反序的?
96. Java中，怎么打印出一个字符串的所有排列?
97. Java中，怎样才能打印出数组中的重复元素?
98. Java中如何将字符串转换为整数?
99. 在没有使用临时变量的情况如何交换两个整数变量的值?
100. 接口是什么?为什么要使用接口而不是直接使用具体类?
101. Java中，抽象类与接口之间有什么不同?
102. 除了单例模式，你在生产环境中还用过什么设计模式?
103. 你能解释一下里氏替换原则吗?
104. 什么情况下会违反迪米特法则?为什么会有这个问题?
105. 适配器模式是什么?什么时候使用?
106. 什么是“依赖注入”和“控制反转”?为什么有人使用?
107. 抽象类是什么?它与接口有什么区别?你为什么要使用过抽象类?
108. 构造器注入和setter依赖注入，那种方式更好?
109. 依赖注入和工程模式之间有什么不同?
110. 适配器模式和装饰器模式有什么区别?
111. 适配器模式和代理模式之前有什么不同?
112. 什么是模板方法模式?
113. 什么时候使用访问者模式?
114. 什么时候使用组合模式?
115. 继承和组合之间有什么不同?
116. 描述Java中的重载和重写?
117. Java中，嵌套公共静态类与顶级类有什么不同?
118. OOP中的组合、聚合和关联有什么区别?
119. 给我一个符合开闭原则的设计模式的例子?
120. 抽象工厂模式和原型模式之间的区别?
121. 嵌套静态类与顶级类有什么区别?
122. 你能写出一个正则表达式来判断一个字符串是否是一个数字吗?
123. Java中，受检查异常和不受检查异常的区别?
124. Java中，throw和throws有什么区别
125. Java中，Serializable与Externalizable的区别?
126. Java中，DOM和SAX解析器有什么不同?
127. 说出JDK 1.7中的三个新特性?
128. 说出5个JDK1.8引入的新特性?
129. Java中,Maven和ANT有什么区别?

Spring面试题(一)

1. 一般问题
    1.1. 不同版本的Spring Framework有哪些主要功能?
    1.2. 什么是Spring Framework?
    1.3. 列举Spring Framework的优点。
    1.4. Spring Framework有哪些不同的功能?
    1.5. Spring Framework中有多少个模块,它们分别是什么?
    1.6. 什么是Spring配置文件?
    1.7. Spring应用程序有哪些不同组件?
    1.8. 使用Spring有哪些方式?
2. 依赖注入(Ioc)
    2.1. 什么是SpringIOC容器?
    2.2. 什么是依赖注入?
    2.3. 可以通过多少种方式完成依赖注入?
    2.4. 区分构造函数注入和setter注入。
    2.5. spring中有多少种IOC容器?
    2.6. 区分BeanFactory和ApplicationContext。
    2.7. 列举IoC的一些好处。
    2.8. Spring IoC的实现机制。
3. Beans
    3.1. 什么是spring bean?
    3.2. spring提供了哪些配置方式?
    3.3. spring支持集中bean scope?
    3.4. spring bean容器的生命周期是什么样的?
    3.5. 什么是spring的内部bean?
    3.6. 什么是spring装配
    3.7. 自动装配有哪些方式?
    3.8. 自动装配有什么局限?
4. 注解
    4.1. 什么是基于注解的容器配置
    4.2. 如何在spring中启动注解装配?
    4.3. @Component,@Controller,@Repository,@Service有何区别?
    4.4. @Required注解有什么用?
    4.5. @Autowired注解有什么用?
    4.6. @Qualifier注解有什么用?
    4.7. @RequestMapping注解有什么用?
5. 数据访问
    5.1. spring DAO有什么用?
    5.2. 列举Spring DAO抛出的异常。
    5.3. spring JDBC API中存在哪些类?
    5.4. 使用Spring访问Hibernate的方法有哪些?
    5.5. 列举spring支持的事务管理类型
    5.6. spring支持哪些ORM框架
6. AOP
    6.1. 什么是AOP?
    6.2. 什么是Aspect?
    6.3. 什么是切点(JoinPoint)
    6.4. 什么是通知(Advice)?
    6.5. 有哪些类型的通知(Advice)?
    6.6. 指出在spring aop中concern和cross-cutting concern的不同之处。
    6.7. AOP有哪些实现方式?
    6.8. Spring AOP and AspectJ AOP有什么区别?
    6.9. 如何理解Spring中的代理?
    6.10. 什么是编织(Weaving)?
7. MVC
    7.1. Spring MVC框架有什么用?
    7.2. 描述一下DispatcherServlet的工作流程
    7.3. 介绍一下WebApplicationContext

Spring面试题(二)

1. 什么是spring?
2. 使用Spring框架的好处是什么?
3. Spring由哪些模块组成?
4. 核心容器(应用上下文)模块。
5. BeanFactory-BeanFactory实现举例。
6. XMLBeanFactory
7. 解释AOP模块
8. 解释JDBC抽象和DAO模块。
9. 解释对象/关系映射集成模块。
10. 解释WEB模块。
11. Spring配置文件
12. 什么是Spring IOC容器?
13. IOC的优点是什么?
14. ApplicationContext通常的实现是什么?
15. Bean工厂和Application contexts有什么区别?
16. 一个Spring的应用看起来象什么?
17. 什么是Spring的依赖注入?
18. 有哪些不同类型的IOC(依赖注入)方式?
19. 哪种依赖注入方式你建议使用，构造器注入，还是Setter方法注入?
20. 什么是Spring beans?
21. 一个Spring Bean定义包含什么?
22. 如何给Spring容器提供配置元数据?
23. 你怎样定义类的作用域?
24. 解释Spring支持的几种bean的作用域。
25. Spring框架中的单例bean是线程安全的吗?
26. 解释Spring框架中bean的生命周期。
27. 哪些是重要的bean生命周期方法?你能重载它们吗?
28. 什么是Spring的内部bean?
29. 在Spring中如何注入一个java集合?
30. 什么是bean装配?
31. 什么是bean的自动装配?
32. 解释不同方式的自动装配。
33. 自动装配有哪些局限性?
34. 你可以在Spring中注入一个null和一个空字符串吗?
35. 什么是基于Java的Spring注解配置?给一些注解的例子
36. 什么是基于注解的容器配置?
37. 怎样开启注解装配?
38. @Required注解
39. @Autowired注解
40. @Qualifier注解
41. 在Spring框架中如何更有效地使用JDBC?
42. JdbcTemplate
43. Spring对DAO的支持
44. 使用Spring通过什么方式访问Hibernate?
45. Spring支持的ORM
46. 如何通过HibernateDaoSupport将Spring和Hibernate结合起来?
47. Spring支持的事务管理类型
48. Spring框架的事务管理有哪些优点?
49. 你更倾向用那种事务管理类型?
50. 解释AOP
51. Aspect切面
52. 在SpringAOP中，关注点和横切关注的区别是什么?
53. 连接点
54. 通知
55. 切点
56. 什么是引入?
57. 什么是目标对象?
58. 什么是代理?
59. 有几种不同类型的自动代理?
60. 什么是织入。什么是织入应用的不同点?
61. 解释基于XML Schema方式的切面实现。
62. 解释基于注解的切面实现
63. 什么是Spring的MVC框架?
64. DispatcherServlet
65. WebApplicationContext
66. 什么是Spring MVC框架的控制器?
67. @Controller注解
68. @RequestMapping注解

微服务面试题

1. 您对微服务有何了解?
2. 微服务架构有哪些优势?
3. 微服务有哪些特点?
4. 设计微服务的最佳实践是什么?
5. 微服务架构如何运作?
6. 微服务架构的优缺点是什么?
7. 单片，SOA和微服务架构有什么区别?
8. 在使用微服务架构时，您面临哪些挑战?
9. SOA和微服务架构之间的主要区别是什么?
10. 微服务有什么特点?
11. 什么是领域驱动设计?
12. 为什么需要域驱动设计(DDD)?
13. 什么是无所不在的语言?
14. 什么是凝聚力?
15. 什么是耦合?
16. 什么是REST/RESTful以及它的用途是什么?
17. 你对Spring Boot有什么了解?
18. 什么是Spring引导的执行器?
19. 什么是Spring Cloud?
20. Spring Cloud解决了哪些问题?
21. 在Spring MVC应用程序中使用WebMvcTest注释有什么用处?
22. 你能否给出关于休息和微服务的要点?
23. 什么是不同类型的微服务测试?
24. 您对Distributed Transaction有何了解?
25. 什么是Idempotence以及它在哪里使用?
26. 什么是有界上下文?
27. 什么是双因素身份验证?
28. 双因素身份验证的凭据类型有哪些?
29. 什么是客户证书?
30. PACT在微服务架构中的用途是什么?
31. 什么是OAuth?
32. 康威定律是什么?
33. 合同测试你懂什么?
34. 什么是端到端微服务测试?
35. Container在微服务中的用途是什么?
36. 什么是微服务架构中的DRY?
37. 什么是消费者驱动的合同(CDC)?
38. Web，RESTful API在微服务中的作用是什么?
39. 您对微服务架构中的语义监控有何了解?
40. 我们如何进行跨功能测试?
41. 我们如何在测试中消除非决定论?
42. Mock或Stub有什么区别?
43. 您对Mike Cohn的测试金字塔了解多少?
44. Docker的目的是什么?
45. 什么是金丝雀释放?
46. 什么是持续集成(CI)?
47. 什么是持续监测?
48. 架构师在微服务架构中的角色是什么?
49. 我们可以用微服务创建状态机吗?
50. 什么是微服务中的反应性扩展?

Linux面试题

1. 绝对路径用什么符号表示?当前目录、上层目录用什么表示?主目录用什么表示?切换目录用什么命令?
2. 怎么查看当前进程?怎么执行退出?怎么查看当前路径?
3. 怎么清屏?怎么退出当前命令?怎么执行睡眠?怎么查看当前用户id?查看指定帮助用什么命令?
4. Ls命令执行什么功能?可以带哪些参数,有什么区别?
5. 建立软链接(快捷方式),以及硬链接的命令。
6. 目录创建用什么命令?创建文件用什么命令?复制文件用什么命令?
7. 查看文件内容有哪些命令可以使用?
8. 随意写文件命令?怎么向屏幕输出带空格的字符串，比如"hello world"?
9. 终端是哪个文件夹下的哪个文件?黑洞文件是哪个文件夹下的哪个命令?
10. 移动文件用哪个命令?改名用哪个命令?
11. 复制文件用哪个命令?如果需要连同文件夹一块复制呢?如果需要有提示功能呢?
12. 删除文件用哪个命令?如果需要连目录及目录下文件一块删除呢?删除空文件夹用什么命令?
13. Linux下命令有哪几种可使用的通配符?分别代表什么含义?
14. 用什么命令对一个文件的内容进行统计?(行号、单词数、字节数)
15. Grep命令有什么用?如何忽略大小写?如何查找不含该串的行?
16. Linux中进程有哪几种状态?在ps显示出来的信息中，分别用什么符号表示的?
17. 怎么使一个命令在后台运行?
18. 利用ps怎么显示所有的进程?怎么利用ps查看指定进程的信息?
19. 哪个命令专门用来查看后台任务?
20. 把后台任务调到前台执行使用什么命令?把停下的后台任务在后台执行起来用什么命令?
21. 终止进程用什么命令?带什么参数?
22. 怎么查看系统支持的所有信号?
23. 搜索文件用什么命令?格式是怎么样的?
24. 查看当前谁在使用该主机用什么命令?查找自己所在的终端信息用什么命令?
25. 使用什么命令查看用过的命令列表?
26. 使用什么命令查看磁盘使用空间?空闲空间呢?
27. 使用什么命令查看网络是否连通?
28. 使用什么命令查看ip地址及接口信息?
29. 查看各类环境变量用什么命令?
30. 通过什么命令指定命令提示符?
31. 查找命令的可执行文件是去哪查找的?怎么对其进行设置及添加?
32. 通过什么命令查找执行命令?
33. 怎么对命令进行取别名?
34. du和df的定义，以及区别?
35. awk详解。
36. 当你需要给命令绑定一个宏或者按键的时候，应该怎么做呢?
37. 如果一个linux新手想要知道当前系统支持的所有命令的列表，他需要怎么做?
38. 如果你的助手想要打印出当前的目录栈,你会建议他怎么做?
39. 你的系统目前有许多正在运行的任务，在不重启机器的条件下有什么方法可以把所有正在运行的进程移除呢?
40. bash shell中的hash命令有什么作用?
41. 哪一个bash内置命令能够进行数学运算。
42. 怎样一页一页地查看一个大文件的内容呢?
43. 数据字典属于哪一个用户的?
44. 怎样查看一个linux命令的概要与用法?假设你在/bin目录中偶然看到一个你从没见过的的命令,怎样才能知道它的作用和用法呢?
45. 使用哪一个命令可以查看自己文件系统的磁盘空间配额呢?

Spring Boot面试题

1. 什么是Spring Boot?
2. Spring Boot有哪些优点?
3. 什么是JavaConfig?
4. 如何重新加载SpringBoot上的更改，而无需重新启动服务器?
5. Spring Boot中的监视器是什么?
6. 如何在Spring Boot中禁用Actuator端点安全性?
7. 如何在自定义端口上运行Spring Boot应用程序?
8. 什么是YAML?
9. 如何实现Spring Boot应用程序的安全性?
10. 如何集成Spring Boot和ActiveMQ?
11. 如何使用Spring Boot实现分页和排序?
12. 什么是Swagger?你用Spring Boot实现了它吗?
13. 什么是Spring Profiles?
14. 什么是Spring Batch?
15. 什么是FreeMarker模板?
16. 如何使用Spring Boot实现异常处理?
17. 您使用了哪些starter maven依赖项?
18. 什么是CSRF攻击?
19. 什么是WebSockets?
20. 什么是AOP?
21. 什么是Apache Kafka?
22. 我们如何监视所有Spring Boot微服务?

Spring Cloud面试题

1. 什么是Spring Cloud?
2. 使用Spring Cloud有什么优势?
3. 服务注册和发现是什么意思? Spring Cloud如何实现?
4. 负载平衡的意义什么?
5. 什么是Hystrix?它如何实现容错?
6. 什么是Hystrix断路器?我们需要它吗?
7. 什么是Netflix Feign?它的优点是什么?
8. 什么是Spring Cloud Bus?我们需要它吗?

RabbitMQ面试题

1. 什么是rabbitmq
2. 为什么要使用rabbitmq
3. 使用rabbitmq的场景
4. 如何确保消息正确地发送至RabbitMQ?如何确保消息接收方消费了消息?
5. 如何避免消息重复投递或重复消费?
6. 消息基于什么传输?
7. 消息如何分发?
8. 消息怎么路由?
9. 如何确保消息不丢失?
10. 使用RabbitMQ有什么好处?
11. RabbitMQ的集群
12. mq的缺点

kafka面试题

1. 如何获取topic主题的列表
2. 生产者和消费者的命令行是什么?
3. consumer是推还是拉?
4. 讲讲kafka维护消费状态跟踪的方法
5. 讲一下主从同步
6. 为什么需要消息系统，mysql不能满足需求吗?
7. Zookeeper对于Kafka的作用是什么?
8. 数据传输的事务定义有哪三种?
9. Kafka判断一个节点是否还活着有那两个条件?
10. Kafka与传统MQ消息系统之间有三个关键区别
11. 讲一讲kafka的ack的三种机制
12. 消费者故障，出现活锁问题如何解决?
13. 如何控制消费的位置
14. kafka分布式(不是单机)的情况下，如何保证消息的顺序消费?
15. kafka的高可用机制是什么?
16. kafka如何减少数据丢失
17. kafka如何不消费重复数据?比如扣款，我们不能重复的扣。