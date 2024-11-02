使用Esptool Web页面烧录固件
https://espressif.github.io/esptool-js/

1. 连接USB数据线,打开对应的串口,以最高波特率连接,烧录起始地址为0x0000
2. 点击ChooseFile上传压缩包内对应的.bin文件 (若分压电阻分别为42kΩ和10kΩ,则上传CheapTracker_v2_42k10k.bin,默认为该文件)
3. 先点EraseFlash,再点Program
4. 等待烧录进度完成,输出 Hash of data verified 则烧录成功
