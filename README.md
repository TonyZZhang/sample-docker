参考书籍 《自己动手写Docker》

#第二章
##2.1 Linux Namespace
UTS Namespace 用来隔离nodename和domainname,在uts namespace里面
每个namespace拥有自己的hostname.  
IPC Namespace 用来隔离 System V IPC跟 POSIX message queue  
PID Namespace 用来隔离进程ID.  
Mount Namespace 用来隔离各个进程看到的挂载点视图.  
User Namespace 隔离用户的用户组ID。？用户组ID是什么？
Network Namespace 用来隔离网络栈.

##2.2 Linux Cgroups  
https://blog.csdn.net/weixin_34198453/article/details/92712125

##2.3 Union File System
###2.3.1

#第三章 构造容器
##3.1.1 linux proc文件系统介绍


