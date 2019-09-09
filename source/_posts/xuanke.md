# 按键精灵低定选课实践

由于脚本速度往往远远快于人工，可以尝试使用按键脚本进行低定抢余量。

 大致效果：



![xuanke](..\gif\xuanke.gif)





按键速度配置：

```
i= -1
While i<>0
    i=i-1
//当循环条件成立的时候，反复执行循环体
'==========以下是按键精灵录制的内容==========
MoveTo 2263, 863
Delay 100
    LeftDown 1
        Delay 5
LeftClick 1
    Delay 5
    LeftUp 1
MoveTo 1419, 923
Delay 100
LeftDown 1
Delay 5
LeftClick 1
Delay 5
LeftUp 1
'==========以上是按键精灵录制的内容==========
Wend

```

![1568044154760](..\pic\%5CUsers%5Chc%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5C1568044154760.png)

为了减少浏览器的崩溃可能，推荐使用内网地址 **10.202.78.12** 进入教务网，响应较快。

链接： [按键精灵win版](..\app\qm.zip)