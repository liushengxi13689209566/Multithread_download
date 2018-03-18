# my_easy_curl :
## This is a super super simple multithread downloading tool I wrote by myself.Currently only support multi thread download server files, follow up more functionality, if you like, welcome to join my team. 
### (PS: of course there are still a lot of small bugs, I'm trying to debug it.)
# How to use :
    git clone git@github.com:liushengxi13689209566/Multithread_download.git
    make
    The service side :  ./server 
    The client side  :  ./client 127.0.0.1 5201
    
# The technology used by the server :
    1.epoll 多路复用( ET模式, EPOLLONESHOT事件 )
    2.非 阻 塞 套 接 字 
# The technology used by the client :
    1.条 件 变 量 与 互 斥 锁
    2.多 线 程 编 程  
# Directions for use: 
    The file downloaded by the client exists in the server file directory, the maximum number of threads is not more than 1000, not less than 1





    

