# ProcessManage
## Function
process 启动， 释放， 监控并重启
## Description
python multiprocessing Process Manage class
## NOTE
在多进程环境中， 子进程会继承复制父进程的资源， 当父进程中调用python signal模块注册信号处理，子进程将继承父进程的处理方式，所以在父进程中处理信号时需要考虑当前进程是否是主进程
