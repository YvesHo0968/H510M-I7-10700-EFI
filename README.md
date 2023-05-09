# H510M-i7-10700-OC-EFI
OC 0.9.2
支持的系统 Ventura
[BIOS 设置](https://apple.sqlsec.com/3-%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C/3-1.html) 低版本系统自行测试

## 硬件参数

- CPU：i7-10700
- 显卡：UHD630
- 蓝牙：无
- 以太网：RealtekRTL8111
- 声卡：Realtek ALC897
- USB：usb 3.0

## 正常工作

1. 显卡：核显加速
2. 声卡
3. 以太网
4. USB

## 需要修改
文件地址 OC/config.plist

参考[GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

1. PlatformInfo->Generic->MLB：需要修改；
2. PlatformInfo->Generic->SystemProductName：需要修改；
3. PlatformInfo->Generic->SystemSerialNumber：需要修改；
4. PlatformInfo->Generic->SystemUUID：需要修改。
