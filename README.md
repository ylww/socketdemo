# socketdemo
通过bio、nio、netty方式建立socket的echo应用

## 基本原理
Server端需要ServerSocket和socket，其中ServerSocket处理accept，而socket处理io操作

![](http://javayaz.com/wp-content/uploads/2014/12/java_images/2_ID58_Server.jpg)


## 文件夹说明
- bio文件夹：使用ServerSocket和Socket
- nio文件夹：使用ServerSocketChannel和SocketChannel
- netty文件夹：使用NioServerSocketChannel和NioSocketChannel

