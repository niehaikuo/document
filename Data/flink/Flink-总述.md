本f地运行

下载（项目免安装）

启动

运行：

1.运行demo即可（flink.bat run ../examples/batch/WordCount.jar）[参考demo运行](https://blog.csdn.net/xichengqc/article/details/91376187)。

2.使用netcat 检测实时输入字符串 [netcat安装]()

​	（1）使用netcat进行9000 端口的监听 nc -l -p 9000

​    （2）运行demo的jar包，flink run examples/streaming/SocketWindowWordCount.jar --port 9000

​	（3）在启动的java.exe窗口，查看字符串的输出。

​	 [参考码云 Flink 渐进式学习教程](https://my.oschina.net/u/3831696?tab=newest&catalogId=6554091)



## 阶段二

[Flink专栏](http://www.54tianzhisheng.cn/2019/12/31/Flink-resources/)

读取flink数据，写入到kafka，并从kafka进行消费。

从kafka读取数据，并写入。

1.flink 从0到1学习。使用flink对接kafka，Redis，等。

flink并行数据源是指什么？

fllink的数据源（jvm的collector，file，kafka等）

flink的sink。数据处理输出。

flink 的计算transformation 几种函数。




<font color=red>**（疑问如何求多个数据的平均值：单纯使用reduce的话只能计算最近两数据的平均值）**</font>




streamWindow流处理窗口

