# multi_threading
《C++并发编程实战》的读书笔记，供以后工作中查阅。
## 第一章
- 何谓并发和多线程
	并发：单个系统里同时执行多个独立的活动。
	多线程：每个线程相互独立运行，且每个线程可以运行不同的指令序列。但进程中所有线程都共享相同的地址空间，并且从所有的线程中访问到大部分数据。
- 为什么要在应用程序中使用并发和多线程
	关注点分离（DVD程序逻辑分离）和性能（加快程序运行速度）
- 一个简单的C++多线程程序是怎么样的
	[一个简单的Hello,Cuncurrent World程序](https://github.com/xuyicpp/multi_threading/blob/master/chapter01/example1_1.cpp)

## 第二章
- 启动线程，以及让各种代码在新线程上运行的方法
- 等待线程完成并让它自动运行
- 唯一地标识线程

