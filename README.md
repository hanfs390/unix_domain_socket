# unix_domain_socket
 communication  demo of unix domain socket 


UDS传输不需要经过网络协议栈,不需要打包拆包等操作,只是数据的拷贝过程
UDS分为SOCK_STREAM(流套接字)和SOCK_DGRAM(数据包套接字),由于是在本机通过内核通信,不会丢包也不会出现发送包的次序和接收包的次序不一致的问题

