# JavaStarter
最开始写博客的目的就是为了学习和记录，后来发现虽然写了这么多，但是没有系统性地进行整理，因此我建立了JavaStarter系列。希望在学习或面试中都对大家有所帮助。

后续所有文章首发微信公众号《Java鱼仔》，欢迎搜索关注或者扫码关注，有任何问题或需要沟通的都可以在这里找到我。

<p align="center">
     <img src="https://github.com/OliverLiy/JavaStarter/blob/main/images/qrcode_for_gh_544708444941_344.jpg" width=""/>
</p>

<p align="center">
  <a href="https://juejin.cn/user/3122268755736119"><img src="https://img.shields.io/badge/juejin-掘金-blue.svg" alt="公众号"></a>
  <a href="https://blog.csdn.net/qq_41973594"><img src="https://img.shields.io/badge/csdn-CSDN-red.svg" alt="投稿"></a>
  <a href="https://my.oschina.net/u/4873431"><img src="https://img.shields.io/badge/oschina-开源中国-green" alt="投稿"></a>
</p>

# 目录

**注 : 文章持续更新中，没有链接的请等待**

- 计算机核心基础

  - 计算机操作系统
     
  - 计算机网络
     - [作为一个程序员需要了解多少网络方面的基础？网络基础总结（不断更新）](https://mp.weixin.qq.com/s/C7CXHAx_6qQNEDKsqY-fxw)
  
  - 计算机组成原理
     
  - 数据结构
     
- Java核心基础
     
  - 基础篇
     - [final 在 java 中有什么作用？](https://mp.weixin.qq.com/s/BLP3bG1ibNM1ly0FPAQS1g)
     - [String str=“i”与 String str=new String(“i”)一样吗？](https://mp.weixin.qq.com/s/lWxKX1VVE2jQ0qi71F__Gw)
     - [两个对象的 hashCode()相同，则 equals()也一定为 true吗？](https://mp.weixin.qq.com/s/K8RuW1wsP0LRFdp8QgYFaw)
     - [抽象类必须要有抽象方法吗？抽象类能使用 final 修饰吗？](https://mp.weixin.qq.com/s/s2adv99CRvA69vFAVYAnCQ)
     - [JavaIO的整体结构以及File类的使用](https://blog.csdn.net/qq_41973594/article/details/104849452)
     - [快速学懂字节流与字符流](https://blog.csdn.net/qq_41973594/article/details/104867904)
     - [尽可能将BIO、NIO、AIO讲得通俗易懂](https://blog.csdn.net/qq_41973594/article/details/104943131)
     - [java反射机制详解](https://mp.weixin.qq.com/s/ZBOmJ4gwpsJyQ1HF63K6Ug)
     - [java代理机制详解（静态代理、动态代理：JDK、CGlib）](https://blog.csdn.net/qq_41973594/article/details/104118797)
     - [一篇文章带你了解cloneable接口、浅拷贝、深拷贝](https://mp.weixin.qq.com/s/ceEjFw15otMGfoSKJpf0zQ)
     - [谈一谈session和cookie的区别，以及session的实现机制](https://mp.weixin.qq.com/s/i_Rc044w0jsaB36ABQELJA)
     - [你知道迭代器 Iterator 是什么吗？](https://mp.weixin.qq.com/s/HSL1WE-xra_IOF59a2IlmQ)
     - [看完这篇类的实例化顺序，考执行顺序的面试题就难不倒你了](https://mp.weixin.qq.com/s/iuVsZmN6P3CY6dnFHmqoeQ)
     - [什么是接口的幂等性，如何实现接口幂等性？一文搞定](https://mp.weixin.qq.com/s/DQ_5uydWw9MelzgeFS45Wg)
     - [线程的 run()和 start()有什么区别？sleep() 和 wait() 有什么区别？](https://mp.weixin.qq.com/s/HE-vK8GR9xI9HeKWS476Jw)
     
  - 集合类
     - [java集合掌握多少才算合格](https://mp.weixin.qq.com/s/pG3PwS4IKqUIqJGYSmxtzg)
     - [ArrayList、Vector、LinkedList的底层源码分析和对比](https://mp.weixin.qq.com/s/pt-dH2lSQbv3MjgZeeJryA)
     - [Set接口及其实现类HashSet、TreeSet的底层结构与区别](https://mp.weixin.qq.com/s/5bFCcrPGcjUssb9RbtEkuw)
     - [HashMap、HashTable、TreeMap的底层源码分析和对比](https://mp.weixin.qq.com/s/G3cfPJoSo3ctdZu3Qv5gwg)
     - [四千字从源码分析ConcurrentHashMap的底层原理（JDK1.8）](https://mp.weixin.qq.com/s/7qGxMr3ZP_xt97-V5pm8Ow)
  
  - JVM虚拟机
     - [JVM的内存分代，这篇文章帮你理一理](https://mp.weixin.qq.com/s/gol03hmwu34n5-TRNLm2FQ)
     - [JVM垃圾回收机制是怎样的，何时触发YoungGC或FullGC操作，一文搞定](https://mp.weixin.qq.com/s/zelYGONiIWGnUa1NgtQOMQ)
     - [关于垃圾收集器你了解多少？一文总结七大垃圾收集器](https://mp.weixin.qq.com/s/Qj9BJvlp_X2qpohX0w-ILA)
     - [图解类加载器和双亲委派机制，一看就懂](https://mp.weixin.qq.com/s/U41G0R-SNqNKaMEksuj78A)
     - [类加载的全过程，我给大家理一理](https://mp.weixin.qq.com/s/ys1_2panH5RQiACRNcGfXA)
  
  - Java并发
     - [什么是乐观锁、什么是悲观锁，两种锁在Java中的具体应用场景有哪些](https://mp.weixin.qq.com/s/3KV3kpqD45ll4H7Kmy7Clw)
     - [你能说出四种创建线程的方式吗？](https://mp.weixin.qq.com/s/XiFGVTI5--RANi5sHAIkjA)
     - [说一下runnable 和 callable 有什么区别？Future是什么？](https://mp.weixin.qq.com/s/OyCm-mM4wveceGk6Ehg9Ig)
     - [如何让多个线程按顺序执行？](https://mp.weixin.qq.com/s/oVnkrDsFo3LjLlr03rOZnw)
     - [面试官：不会真有人不知道什么是线程池吧？](https://blog.csdn.net/qq_41973594/article/details/106982052)
     - [面试官：我问的是Java内存模型，你回答堆栈方法区干嘛？](https://mp.weixin.qq.com/s/4NHC9Fmk7eiiI8UHrnYNOA)
     - [指令重排序、内存屏障很难？看完这篇你就懂了！](https://mp.weixin.qq.com/s/YBr32zvQ00EesLRUnx__Jw)
     - [Volatile只会用不知道原理？一篇文章带你深究volatile](https://mp.weixin.qq.com/s/IOD6l9s0JN9VJXNlm07yJQ)
     - [有关synchronized锁的知识点，我用一篇文章总结了](https://mp.weixin.qq.com/s/hy42BV48RjOzkkXeDL-wZA)
     
  

- 框架的艺术

  - Spring
     
  
  - Mybatis
     - [Mybatis的原理介绍及超详细使用](https://blog.csdn.net/qq_41973594/article/details/109557341)
     - [Mybatis增删改查，这一篇足以](https://blog.csdn.net/qq_41973594/article/details/109589066)
     - [Mybatis配置详细解析](https://blog.csdn.net/qq_41973594/article/details/109655779)
     - [MyBatis实现复杂环境的Sql查询](https://blog.csdn.net/qq_41973594/article/details/109683869)
     - [Mybatis日志原来是这样使用的](https://blog.csdn.net/qq_41973594/article/details/109711808)
     - [Mybatis动态Sql详解](https://blog.csdn.net/qq_41973594/article/details/109752413)
     - [Mybatis缓存详解](https://blog.csdn.net/qq_41973594/article/details/109752413)
  
  - SpringMVC
  
  - SpringBoot
     - [如何用SpringBoot（2.3.3版本）快速搭建一个项目？文末有小彩蛋](https://mp.weixin.qq.com/s/dEpH1QYIpp46eIbZ2WKZPw)
     - [一步步带你看SpringBoot（2.3.3版本）自动装配原理](https://mp.weixin.qq.com/s/FUAs_tXX7jjyAiCnEk2qSg)
     - [SpringBoot配置文件及自动配置原理详解，这应该是SpringBoot最大的优势了吧](https://mp.weixin.qq.com/s/XylqpV7ui_wNC46UYkDIBA)
     - [SpringBoot整合jdbc、durid、mybatis详解，数据库的连接就是这么简单](https://mp.weixin.qq.com/s/FCYkNcba16POY_GgOMeZ0g)
     - [SpringBoot整合SpringSecurity详解，认证授权从未如此简单](https://mp.weixin.qq.com/s/nh3xVtl-5qmPS3Acmqgopw)
     - [SpringBoot整合Shiro详解，还在自己写登陆注册早落伍了](https://mp.weixin.qq.com/s/xsgZZYFDEnI51m2Wyh4dxg)
     - [SpringBoot如何实现异步、定时任务？](https://mp.weixin.qq.com/s/xqb32G64rwfdfOUla6ZRgg)
  
  - SpringCloud
     - [使用idea搭建第一个微服务项目（附源码）](https://blog.csdn.net/qq_41973594/article/details/103377731)
     - [Eureka基础与进阶实战](https://blog.csdn.net/qq_41973594/article/details/103432357)
     - [ribbon的服务调用和负载均衡](https://blog.csdn.net/qq_41973594/article/details/103481333)
     - [Feign的入门和高级使用](https://blog.csdn.net/qq_41973594/article/details/103520168)
     - [Hystrix的入门和高级使用](https://blog.csdn.net/qq_41973594/article/details/103559788)
     - [SpringCloud之微服务网关的入门与进阶（请求过滤、网关限流）](https://blog.csdn.net/qq_41973594/article/details/103609543)
  
  - Mq
     - [RabbitMQ的了解安装和使用](https://blog.csdn.net/qq_41973594/article/details/104363409)
     - [简单队列详解](https://blog.csdn.net/qq_41973594/article/details/104381204)
     - [工作队列详解](https://blog.csdn.net/qq_41973594/article/details/104434915)
     - [发布-订阅模型详解](https://blog.csdn.net/qq_41973594/article/details/104451416)
     - [routing路由模式和Topic主题模式](https://blog.csdn.net/qq_41973594/article/details/104486338)
     - [RabbitMQ消息确认机制](https://blog.csdn.net/qq_41973594/article/details/104562486)
  
  - Zookeeper
  
  - Netty
  
  
- 这就是数据库

  - Mysql
     - [Mysql的索引调优详解：如何去创建索引以及避免索引失效](https://blog.csdn.net/qq_41973594/article/details/105045799)
     - [都2020年了，你还不知道count(1)和count(*)谁效率更高吗？](https://blog.csdn.net/qq_41973594/article/details/106796388)
  
  - Redis
     - [redis入门到精通系列（一）：入门redis看这一篇就够了](https://mp.weixin.qq.com/s/T4nUo0PU9cN7qpWW5jw3UA)
     - [redis入门到精通系列（二）：redis操作的两个实践案例](https://mp.weixin.qq.com/s/4c4O1bFbh28aRt5eltoduA)
     - [redis入门到精通系列（三）：key的通用操作和redis内部db的通用操作](https://mp.weixin.qq.com/s/FFCKulAp1DMB40rzEWeK4A)
     - [redis入门到精通系列（四）：Jedis--使用java操作redis详解](https://mp.weixin.qq.com/s/u2STtic9_Aha43Z_EQga1g)
     - [redis入门到精通系列（五）：redis的持久化看这一篇就够了](https://mp.weixin.qq.com/s/COoiYj24Gg7WqVHkVOwcsQ)
     - [redis入门到精通系列（六）：redis的事务详解](https://mp.weixin.qq.com/s/EBB1-eirR1VRA1mAJPO6BA)
     - [redis入门到精通系列（七）：redis高级数据类型详解（BitMaps,HyperLogLog,GEO）](https://mp.weixin.qq.com/s/nFGFaBGMpbve6d7eeYv1jQ)
     - [redis入门到精通系列（八）：redis的高可用--主从复制详解](https://mp.weixin.qq.com/s/7wcs22Fo0CdtDq1GapIHcA)
     - [redis入门到精通系列（九）：redis哨兵模式详解](https://mp.weixin.qq.com/s/ShzzyI_TaAqD5cBN_LVnGw)
     - [redis入门到精通系列（十）：springboot快速集成redis](https://mp.weixin.qq.com/s/2e4in0zi8ye6HuChzu4HgQ)
     - [redis入门到精通系列（十一）：redis的缓存穿透、缓存击穿以及缓存雪崩](https://mp.weixin.qq.com/s/E48J2R9roj8gV5soOC4b4A)
     - [redis入门到精通系列（十二）：看完这一篇文章别再说不懂布隆过滤器](https://mp.weixin.qq.com/s/Z0Td6XgQ36imsQaIN-YzmA)
  

- 每个程序员都要会Linux


- 实战项目

  - 基于SpringBoot和BootStrap的论坛网址
     - [基于SpringBoot和BootStrap的全栈论坛网站](https://blog.csdn.net/qq_41973594/article/details/103288287)
     - [（一）：准备阶段](https://blog.csdn.net/qq_41973594/article/details/102967807)
     - [（二）：后端人员如何快速使用BootStrap](https://blog.csdn.net/qq_41973594/article/details/102984261)
     - [（三）：登陆注册以及cookies的功能完成](https://blog.csdn.net/qq_41973594/article/details/103004974)
     - [（四）：完成问题发布功能](https://blog.csdn.net/qq_41973594/article/details/103043298)
     - [（五）：完成首页展示以及分页功能](https://blog.csdn.net/qq_41973594/article/details/103079089)
     - [（六）：完成个人中心、问题详情和问题编辑](https://blog.csdn.net/qq_41973594/article/details/103133266)
     - [（七）：完成回复和二级回复功能](https://blog.csdn.net/qq_41973594/article/details/103232086)
     - [（八）：完成回复通知的功能](https://blog.csdn.net/qq_41973594/article/details/103287161)
     
  - 搭建基于SpringBoot的秒杀后台项目
     - [(一)：项目准备](https://blog.csdn.net/qq_41973594/article/details/107774491)
     - [(二)：快速搭建一个SpringBoot项目](https://blog.csdn.net/qq_41973594/article/details/107799310)
     - [(三)：首页、详情页编写](https://blog.csdn.net/qq_41973594/article/details/107824871)
     - [(四)：雪花算法生成订单号以及抢购功能实现](https://blog.csdn.net/qq_41973594/article/details/107876913)
     - [(五)：基于Shiro的人员登陆认证](https://blog.csdn.net/qq_41973594/article/details/107895987)
     - [(六)：使用RabbitMQ让订单指定时间后失效](https://blog.csdn.net/qq_41973594/article/details/107946207)
     - [(七)：高并发导致超卖问题分析处理](https://blog.csdn.net/qq_41973594/article/details/108030153)
     - [(八)：通过分布式锁解决多线程导致的问题](https://blog.csdn.net/qq_41973594/article/details/108030244)
     
 
   
- 开发工具大全
     - [一个包含多种Get请求和Post请求的工具类](https://blog.csdn.net/qq_41973594?spm=1000.2115.3001.5113)

- 我的程序人生
     - [作为一名普通本科计算机专业学生，我大学四年到底走了多少弯路](https://blog.csdn.net/qq_41973594/article/details/103232236)
     - [应届毕业生因为疫情休息在家，可以通过哪些途径提高自己？](https://blog.csdn.net/qq_41973594/article/details/104591075)
     - [JAVA实习生刚进公司主要做些什么？以及进入职场后我的心理变化](https://blog.csdn.net/qq_41973594/article/details/105565105)
     - [工作中只需要增删改查的程序员，别安于现状](https://blog.csdn.net/qq_41973594/article/details/109541193)
     - [坚持写技术博客，我得到了什么？](https://blog.csdn.net/qq_41973594/article/details/110147766)
     

# 祝福

我一直相信一句话，**你会累是因为你在走上坡路**，希望我的这个系列文章能够帮助到点开的你
