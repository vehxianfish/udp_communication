##udp和通讯
#server.cpp为了解决端口的问题在里面加了信号函数，
#一接收到ctrl+c的信号就触发信号，然后调用信号函数
#将循环条件flag=0，跳出循环，关闭套接字。
#udp_broadcast.cpp是客户端，里面是广播的模式

