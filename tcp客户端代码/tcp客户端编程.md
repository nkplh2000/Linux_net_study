# Linux网络编程学习

##### 1、tcp客户端代码的编写

![1647962326581](./1647962326581.png)

~~~ shell
 n = read(sock_fd, buf, sizeof(buf));
 write(STDOUT_FILENO, buf, n);
表示从socket读入数据到终端，再从写入终端。
~~~

