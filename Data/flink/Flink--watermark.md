参考：

##### [watermark](https://blog.csdn.net/lmalds/article/details/52704170)



watermark:

结合window，进行数据乱序处理计算。

窗口的大小是自定义的，配置好后与数据流的event_time无关，固定的window_start_time和window_end_time.



窗口触发计算的条件：

- 数据的event_time < watermark
- 数据所在窗口的window_end_time < watermark
- 当前窗口中存在数据



##### [allowedLateness详细介绍及思考](https://blog.csdn.net/lmalds/article/details/55259718)



##### 什么是TumblingEventTime窗口？

窗口开始，结束时间与eventTime无关。



##### 什么是EventTimeSessionWindows？

eventTime 为窗口开始时间，eventTime+windowSize为窗口结束时间。

会话窗口存在窗口的merge。





窗口大小为10秒，eventTime的时间是2020-01-13 13：41：3

tumblingEventTime窗口范围（13：41：00 ---13：41：10）

sessionwindow窗口范围（13：41：3---13：41：13）



概念：Trigger是什么？

计算的触发器。





