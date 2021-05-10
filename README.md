# Bananapi小游戏，打地鼠

* 大学期间2015年1月玩Bananapi的时候写的，年代久远，现在挖出来保存一下
* game1.c是游戏源码
* oled.c是OLED的驱动demo
## 说明

* BPI是对拍死的BPI的计数,对应最终的成绩
* RANK是难度 数值越低难度越高 每当打死10个BPI以后就会减一即难度高一级 默认初始化RANK等于15
* DIE是存在的BPI数量,一旦数量大于或者等于5就GameOver了..........
* 最后会把最终成绩打印在屏幕和终端上

![i](https://github.com/guanglun/Whac-a-BPI/blob/master/show1.png)
![i](https://github.com/guanglun/Whac-a-BPI/blob/master/show2.png)
![i](https://github.com/guanglun/Whac-a-BPI/blob/master/show3.png)
![i](https://github.com/guanglun/Whac-a-BPI/blob/master/show4.png)
![i](https://github.com/guanglun/Whac-a-BPI/blob/master/show5.png)