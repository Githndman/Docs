
## 外观介绍

![](readme/Interface_CN.jpg)

Bit 采用 ESP-WROOM-32 （ESP32）模组作为核心进行设计，拥有 40nm 工艺、使用 Tensilica LX6 双核32位处理器，频率高达 240 MHz，带有 32 个 I/O 引脚，支持 2.4G Wi-Fi 、蓝牙 4.0 以上等多种通信方式，具备 448KB ROM 和 520 KB SRAM 的内存容量。

Bit 开发板长 5 公分宽 5 公分，重量约 10 ~ 12 公克，除了下方 20 Pin 的「金手指接口」，更内置一个 25 颗全彩 LED 灯的矩阵，两个光敏电阻、两个按钮开关、一个温度感应电阻、一个蜂鸣器和一个九轴传感器 ( 三轴加速度、三轴陀螺仪与三轴磁力指南针 )，脚位配置如下：

- 全彩 LED 矩阵：A10 ( GPIO 4 )
- 光敏传感器：左上 A0 ( GPIO 36 )、右上 A3 ( GPIO 39 )
- 按钮开关：按钮 A P5 ( GPIO 35 )、按钮 B P11 ( GPIO 27 )
- 温度传感器：A6 ( GPIO 34 )
- 蜂鸣器：P0 ( GPIO 25 )
- 九轴传感器 MPU-9250：P20 ( GPIO 21 )、P19 ( GPIO 22 )

## 拓展引脚

![](readme/goldfinger.jpg)

![](readme/pin-define.jpg)

### LED 编号

板子按照 5 * 5 排列方式焊接了 25 颗(编号 0 ~ 24 ) 1600 万色全彩 LED (WS2812) ，所有的 LED 的控制仅使用一个引脚 (GPIO 4) 即可控制。

![](readme/product.jpg)

板子正面 LED 序号排布方式如下（5 * 5）

![](readme/table.png)

（将板子正面朝向自己，并结合底盘金手指可知其位置）

## 版本区别

板子分 1.2 和 1.4 版本等多个版本，版本号标识在板子背面右下角。

![](readme/version.jpg)

## 硬件设计

### 引脚占用

![](readme/extern.png)

### 丝印图

![](readme/bot.png)

![](readme/top.png)

### 硬件资料

- [BPI-WEBDUINO-BIT-V1_2](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/BPI-WEBDUINO-BIT-V1_2.pdf)

- [BPI-WEBDUINO-BIT-V1_4](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/BPI-WEBDUINO-BIT-V1_4.pdf)

- [Buzzer-SS-S050020Z-120](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/Buzzer-SS-S050020Z-120.pdf)

- [CH340DS1-ch](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/CH340DS1-ch.pdf)

- [CH340DS1-en](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/CH340DS1-en.pdf)

- [esp32_hardware_design_guidelines_en](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/esp32_hardware_design_guidelines_en.pdf)

- [ESP32-datesheet_english](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/ESP32-datesheet_english.pdf)

- [esp-wroom-32_datasheet_cn](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/esp-wroom-32_datasheet_cn.pdf)

- [LightSensor-PTSMD021-0805](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/LightSensor-PTSMD021-0805.pdf)

- [LM1117](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/LM1117.pdf)

- [MPU-9250 Datasheet-v1.1-ch](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/MPU-9250%20Datasheet-v1.1-ch.pdf)

- [MPU-9250 Datasheet-v1.1-en](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/MPU-9250%20Datasheet-v1.1-en.pdf)

- [MPU-9250 Register Map-v1.6](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/MPU-9250%20Register%20Map-v1.6.pdf)

- [NTC-0805-103F-3950F](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/NTC-0805-103F-3950F.pdf)

- [SY7208](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/SY7208.pdf)

- [WS2812B](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/WS2812B.pdf)

- [DS-000189-ICM-20948-v1.3](https://github.com/BPI-STEAM/BPI-BIT-Hardware/tree/master/docs/DS-000189-ICM-20948-v1.3.pdf)

## 相关网站

- [官方中文社区](https://forum.banana-pi.org.cn/c/bpi-bit)
- [官方英文社区](http://forum.banana-pi.org/c/bpi-bit)
- [Webduino 国内版](https://webduino.com.cn/site/)
- [Webduino 国际版](https://webduino.io/)
