## arduino

my personal arduino projects, inclulding :

### weather report

使用arduino + DHT11 +　网络模块组成, 最好能够在openshift上搭建rest服务器实现微薄的定时发送

#### 主要部件

* [以太网模块](http://item.taobao.com/item.htm?id=10745225550)

    价格 35
    
* [DHT11](http://item.taobao.com/item.htm?id=13217697797)

    价格 6.5 
   

    
### GPS logger

通过车载电源, 在启动车的时候自动启动GPS模块, 开始记录轨迹信息, 并且写入到SD卡上, 在停车熄火之后由备用电池供电, 完成最后的写操作, 然后关机, 当SD卡要写满的时候要有提示信息(闪灯?), 最好是能有电池电量检测的功能, 提示更换电池

#### 主要部件

* [GPS扩展板](http://item.taobao.com/item.htm?id=13198221647)

    价格 195
* [GPS天线](http://item.taobao.com/item.htm?id=13198289243)    

    价格 20
    
### 小车

由小车底盘, arduino控制器, android手机, ADK控制板, 舵机, 马达等组成, 基本上是最复杂的一个项目了, 目前的想法主要包括

1. 通过ADK扩展板联通Arduino 和 android
2. android手机可以通过wifi / gprs等方式和外界链接, 以接受控制信号并传至arduino, 这样就可以通过网络的方式来驱动小车的行动了
3. android手机还能够提供视频和拍照的功能, 由小车上的两个舵机来提供了二维的各180度的转动, 可以把android手机放在类似坦克车的炮塔的位置, 能提供左右和上下的摆动, 这样就能方便的环视四周了
4. 另外, android手机上的skype / qq等提供了视频连接等的可能性
5. 同时, android手机上的加速度 / 陀螺仪等传感器均可为arduino提供控制信号
6. android手机也能提供强大的计算能力, 弥补arduino上单片机的不足


#### 主要部件

* [小车底盘和码盘](http://item.taobao.com/item.htm?id=3396039235)  

    价格 198
    
* [两自由度舵机云台](http://item.taobao.com/item.htm?id=13341487163)

    价格 135
    
    主要是用来提供炮塔的功能, 把手机放在这上面
    
* [USB Host Shield](http://item.taobao.com/item.htm?id=13273798482)     

    价格 95, 用来连接arduino和android
    
* [电机驱动板](http://item.taobao.com/item.htm?id=17230672472)

    价格 38
    
    用来驱动上面的舵机云台和小车马达 
   

   
    

    
     
   


