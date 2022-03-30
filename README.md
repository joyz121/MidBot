# 写字机器人

## 结构

  corexy结构的写字机器人，将两个控制电机集中在了中间，极大节省了空间，结构如图：

<img src="img\midbot.jpg" alt="midbot" style="zoom:40%;" />

<img src="img\bot2.png" alt="bot2" style="zoom:14%;" />

## 控制器

移植了Arduino上面非常成熟的GRBL固件到STM32上。

## 写字绘图效果

<img src="img\6BB5EC0014AEC2683363F0402108530F.png" alt="6BB5EC0014AEC2683363F0402108530F" style="zoom:25%;" />

 <img src="img\FE45E3FE8A7B66D830B2A69EA19E08A2.png" alt="FE45E3FE8A7B66D830B2A69EA19E08A2" style="zoom:10%;" />

## 其他

一些缺点：结构不够稳定。

开个脑洞：更改主轴及驱动板可将其改为激光雕刻机、小型贴片机等。