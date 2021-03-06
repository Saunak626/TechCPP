如下是C++后台研发技术路线以及知识点，这里有很多细节，还需要不断完善。 欢迎大家通过[【公众号】](#公众号) 或者加我[【微信】](#微信) 与我交流，一起成长一起进步！


<p align="center">
  <a href="#微信"><img src="https://img.shields.io/badge/wechat-%E5%BE%AE%E4%BF%A1%E7%BE%A4-brightgreen" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E4%BB%A3%E7%A0%81%E9%9A%8F%E6%83%B3%E5%BD%95-blue" alt="公众号"></a>
  <a href="https://www.toutiao.com/c/user/60356270818/#mid=1633692776932365"><img src="https://img.shields.io/badge/toutiao-%E4%BB%A3%E7%A0%81%E9%9A%8F%E6%83%B3%E5%BD%95-yellow" alt=""></a>
  <a href="https://www.zhihu.com/people/sun-xiu-yang-64"><img src="https://img.shields.io/badge/zhihu-知乎-informational" alt=""></a>
  <a href="https://blog.csdn.net/youngyangyang04"><img src="https://img.shields.io/badge/csdn-CSDN-red.svg" alt=""></a>
  <a href="https://cloud.tencent.com/developer/user/2226365/activities"><img src="https://img.shields.io/badge/%E8%85%BE%E8%AE%AF-%E4%BA%91%E7%A4%BE%E5%8C%BA-brightgreen" alt=""></a>
  <a href="https://www.cnblogs.com/youngyangyang04/"><img src="https://img.shields.io/badge/cnblogs-博客园-important.svg" alt=""></a>
</p>

以下没有连接的内容就是还没有写，笔者正在拼命赶稿ing....

# 编程语言C++

* [大厂程序员教你如何学习C++](https://mp.weixin.qq.com/s/Gwtu4mc43YVFlX46yu_WDg)
* C++: volatile static const extern等关键字 
* 常用库函数实现
    * malloc,strcpy,strcmp的实现，常用库函数实现，哪些库函数属于高危函数
* STL原理及实现
* 虚函数的作用和实现原理，什么是虚函数,有什么作用?
    * 纯虚函数，为什么需要纯虚函数？
    * 为什么需要虚析构函数,什么时候不需要?父类的析构函数为什么要定义为虚函数?
    * 内联函数、构造函数、静态成员函数可以是虚函数吗?
    * 构造函数中可以调用虚函数吗?
    * 为什么需要虚继承?虚继承实现原理解析，

* C++ 内存分配机制
* 指针
    * 迭代器与普通指针有什么区别 
    * C++的智能指针及其原理
* override和overload的区别
* 写string类的构造，析构，拷贝函数

# 数据结构与算法
* [leetcode面试高频题目题解](https://github.com/youngyangyang04/leetcode-master)
* [刷leetcode的时候，究竟什么时候可以使用库函数，什么时候不要使用库函数，过来人来说一说](./docs/刷leetcode究竟要不要使用库函数.md)
* [究竟什么是时间复杂度，怎么求时间复杂度，看这一篇就够了](https://mp.weixin.qq.com/s/lYL9TSxLqCeFXIdjt4dcIw)
* [一文带你彻底理解程序为什么会超时](https://mp.weixin.qq.com/s/T-vcJSkq2-0s0bBB-itWbQ)
* [一场面试，带你彻底掌握递归算法的时间复杂度](https://mp.weixin.qq.com/s/Kt-Mvs8LeVqidLGUqySj1g)
* [算法分析中的空间复杂度，你真的会了么？](https://mp.weixin.qq.com/s/sXjjnOUEQ4Gf5F9QCRzy7g)
* [二分法其实很简单，为什么老是写不对！！](https://mp.weixin.qq.com/s/ICdahBRWbbEeEWHKjC8Alw)
* [程序员算法面试中，必须掌握的数组理论知识](https://mp.weixin.qq.com/s/X7R55wSENyY62le0Fiawsg)
* [这五道数组相关的面试题，你一定要会！](https://mp.weixin.qq.com/s/vdKHt2vFSZEouZASjdWieg)
* [关于哈希表，你该了解这些！](https://mp.weixin.qq.com/s/g8N6WmoQmsCUw3_BaWxHZA)
* [这六道哈希表相关的面试题，你一定要会！](https://mp.weixin.qq.com/s/nxuWv5cUhCPSbAdIHtWgSg)
* 精选链表相关的面试题
* 精选字符串相关的面试题
* 精选栈与队列相关的面试题
* 精选二叉树相关的面试题
* 精选递归与回溯面试题

# 设计模式

* [C++设计模式](https://github.com/youngyangyang04/DesignPattern)
* C++单例模式 
* 用C++设计一个不能被继承的类
* 如何定义一个只能在堆上定义对象的类?栈上呢
* 重类构造和析构的顺序

# 操作系统 

* linux的内存管理机制，内存寻址方式，什么叫虚拟内存，内存调页算法，任务调度算法 
* 锁：互斥锁，乐观锁，悲观锁 
    * 死锁必要条件及避免算法 
* 动态链接和静态链接的区别
* 常见的信号、系统如何将一个信号通知到进程
* linux系统的各类同步机制、linux系统的各类异步机制
* 如何实现守护进程
* 标准库函数和系统调用的区别
* 32位系统一个进程最多有多少堆内存
* 五种I/O 模式:阻塞I/O,非阻塞 I/O,I/O 多路复用,信号驱动 I/O,异步 I/O
    * select 模型和 poll 模型，epoll模型
    * socket服务端的实现，select和epoll的区别(必问)
    * epoll哪些触发模式，有啥区别？
* 用户态和内核态的区别
* linux文件系统：inode，inode存储了哪些东西，目录名，文件名存在哪里

# 计算机网络

* TCP和UDP区别
* TCP和UDP头部字节定义 
* TCP和UDP三次握手和四次挥手状态及消息类型 
* time_wait，close_wait状态产生原因，keepalive
* 什么是滑动窗口，超时重传
* 列举你所知道的tcp选项
* connect会阻塞检测及防止，socket什么情况下可读？ 
* socket什么情况下可读？
* connect会阻塞，怎么解决?(必考必问) 
* keepalive是什么？如何使用？
* 长连接和短连接 
* UDP中使用connect的好处 
* DNS和HTTP协议，HTTP请求方式 

# 数据库 

* 谈谈数据库中索引的理解，索引和主键区别
* 现在普通关系数据库用得数据结构是什么类型的数据结构 
* 索引的优点和缺点
* 系型数据库和非关系数据库的特点 
* 乐观锁与悲观锁的区别 
* 数据库范式:第一第二第三范式
* 数据库日志类型作用 
* B TREE 和B+TREE的区别 
* union和join 

# 海量数据处理 

* bitmap 
* Map-Reduce原理 
* BloomFilter原理 
* Trie树原理 
* LSM树原理 

# linux下操作命令以及工具

* [工作中常用的linux 命令](./docs/linux常用操作命令.md)
* 编译工具GCC 
* 调试工具GDB
* 性能优化工具Perf 
* 内存泄露检查工具Valgrind
* makefile编写

# 程序员求职

* [简历模板](https://github.com/youngyangyang04/Markdown-Resume-Template)
* [程序员要如何写简历](https://mp.weixin.qq.com/s/PkBpde0PV65dJjj9zZJYtg)
* [适合新手练习的Github小项目（代码简单，功能实用）](https://mp.weixin.qq.com/s/Bc8Co6TiYxhbrzGLfSrISA)
* [一线互联网公司技术面试的流程以及注意事项](https://mp.weixin.qq.com/s/1VMvQ_6HbVpEn85CNilTiw)
* [如何使用markdown来制作一份自己的简历](https://mp.weixin.qq.com/s/ejvKML-NmEzok15GOzs62A)
* [深圳原来有这么多互联网公司，你都知道么？](https://mp.weixin.qq.com/s/Yzrkim-5bY0Df66Ao-hoqA)

# 程序员的工具

工欲善其事必先利其器

* [vim配置](https://github.com/youngyangyang04/PowerVim)
* [程序员为什么要使用Markdown](https://mp.weixin.qq.com/s/IYbHXABVsFETXW66DYd5nA)
* [程序员应该常逛哪些资讯类网站](https://mp.weixin.qq.com/s/ScMTuJ4WnlQTAbYk0_jeXA)


# 适合新手的开源项目

* [联机五子棋（c实现）](https://github.com/youngyangyang04/Gomoku)
* [fileHttpServer(go语言实现)](https://github.com/youngyangyang04/fileHttpServer)
* [Sqlgen（shell脚本实现的批量操作mysql）](https://github.com/youngyangyang04/PowerSqlgen)
* [单机存储引擎（C++实现的跳表）](https://github.com/youngyangyang04/Skiplist-CPP)
* [NosqlAttack （python实现）](https://github.com/youngyangyang04/NoSQLAttack)

# 关于作者 

大家好，我是程序员Carl，ACM区域赛铜牌获得者，哈工大计算机硕士毕业，先后在腾讯和百度从事后端技术研发，CSDN博客专家。我的微信：

<a name="微信"></a>
<img src="https://img-blog.csdnimg.cn/20200712232919673.jpeg" data-img="1" width="175" height="175">

# 公众号

文章持续更新，可以关注公众号「 代码随想录 」第一时间阅读，关注后回复：「C++」「C++进阶书籍」「算法与数据结构」「简历模板」 等等关键字就可以获得我多年整理出来的学习资料。大厂求职内推也可以在公众号里找到我！

<a name="公众号"></a>
<img src="https://img-blog.csdnimg.cn/20200723191759119.jpg" data-img="1" width="200" height="200">
