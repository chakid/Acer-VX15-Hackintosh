# Acer-VX15-Hackintosh
## 宏碁暗影骑士3的黑苹果EFI文件

电脑配置

|   规格   |               详细信息                |
| :------: | :-----------------------------------: |
| 电脑型号 |    宏碁 Acer 暗影骑士3 (VX5-591G)     |
| 操作系统 |         macOS Mojave 10.14.3          |
|  处理器  |      Intel(R) Core(TM) i5 7300HQ      |
|   内存   |          16 GB DDR4 2400MHz           |
|   硬盘   |        三星 NVMe固态硬盘PM961         |
|   显卡   |         Intel HD Graphics 630         |
|   声卡   |                ALC255                 |
|   网卡   | 已更换苹果原装网卡转接卡(BCM94360CS2) |

### 基本功能都完美



#### 缺陷

1、目前已知缺点，声卡偶尔重启的之后会失效，需再次重启

2、发热量有点大，不知道是不是因为我这是游戏本的原因

3、笔记本显示器亮度关机之后不能保存上次开始之前调好的亮度

4、触摸手势只支持单指和双指

![Zv0C0e.png](https://s2.ax1x.com/2019/07/19/Zv0C0e.png)

![Zv0J10.png](https://s2.ax1x.com/2019/07/19/Zv0J10.png)

![Zv0Fkd.png](https://s2.ax1x.com/2019/07/19/Zv0Fkd.png)

![Zv0Vpt.png](https://s2.ax1x.com/2019/07/19/Zv0Vpt.png)

![Zv0K0g.png](https://s2.ax1x.com/2019/07/19/Zv0K0g.png)

![Zv0LDS.png](https://s2.ax1x.com/2019/07/19/Zv0LDS.png)

![Zv0aBF.png](https://s2.ax1x.com/2019/07/19/Zv0aBF.png)

![Zv00AJ.png](https://s2.ax1x.com/2019/07/19/Zv00AJ.png)

### 更新：

#### 2019-07-20：

#### 1、禁用独显，根据大神 [@7ac](https://github.com/7ack/Acer-V5-572-Hackintosh)的教程，*屏蔽独显：如果使用了WhateverGreen.kext可以直接增加-wegnoegpu启动参数来屏蔽独显*

![Zzk1rF.png](https://s2.ax1x.com/2019/07/20/Zzk1rF.png)

#### 2、定制USB，驱动根据黑果小兵视频 [定制USB驱动](https://www.bilibili.com/video/av40180517?from=search&seid=11665402613183043689)

![Zzka26.png](https://s2.ax1x.com/2019/07/20/Zzka26.png)

#### 3、修复声卡有时重启失效问题：```ACPI设置里面```勾选```修复HPET```

![ZzAo6K.png](https://s2.ax1x.com/2019/07/20/ZzAo6K.png)

### 镜像来源：

##### 黑果小兵的部落阁：https://blog.daliansky.net

##### 装机教程：https://www.jianshu.com/p/be9b16e18b5d