# my_easy_curl :
## This is a super super simple multithread downloading tool I wrote by myself.Currently only support multi thread download server files, follow up more functionality, if you like, welcome to join my team. 
### (PS: of course there are still a lot of small bugs, I'm trying to debug it.)
# How to use :
    git clone git@github.com:liushengxi13689209566/Multithread_download.git
    make
    The service side :  ./server 
    The client side  :  ./client 127.0.0.1 5201
    
# The technology used by the server :
    epoll 多路复用( ET模式, EPOLLONESHOT事件 )
    非阻塞套接字 
# The technology used by the client :
    条件变量与互斥锁
    多线程编程 


    

