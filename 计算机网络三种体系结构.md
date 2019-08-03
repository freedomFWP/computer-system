@[toc]
# 计算机网络体系结构
![计算机网络体系结构](https://img-blog.csdnimg.cn/20190803164007121.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Zlbmd3ZW5wZWk=,size_16,color_FFFFFF,t_70)<center> <font size=5> 计算机网络体系结构 </font> </center>

将OSI体系中的会话层、表示层、应用层合并为应用层后即为五层协议体系，将物理层与数据链路层再合并为网络接口层即为TCP/IP的四层协议体系，TCP/IP协议体系不严格遵循OSI分层概念，应用层可能会直接使用IP层或网络接口层。

## 五层协议体系
以五层协议体系为例，叙述各层功能：

 - 应用层：为**特定应用程序**提供数据传输服务
 - 运输层：为**进程**提供通用数据传输服务
 - 网络层：为**主机**提供数据传输服务
 - 数据链路层：为主机间的多个**链路**提供数据传输服务
 - 物理层：数据比特流
 ## 数据传输流程
 ![层与层之间的数据传输](https://img-blog.csdnimg.cn/20190803170356228.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Zlbmd3ZW5wZWk=,size_16,color_FFFFFF,t_70)
 <center> <font size=5>数据在各层传递过程</font></center>
 
