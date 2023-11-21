# Hackintosh EFI文件 -- 停止维护
## OpenCore版本

[OpenCore-0.7.3-RELEASE](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.3)

## 适用范围

本EFI仅在本人MSI GP76_10UG-426CN (RTX3070) 平台测试
仅供参考，不保证其它平台及同一平台不同环境下完全正常使用

蓝牙：BRCM94360CS2

## 参考内容

[daliansky/OC-little](https://github.com/daliansky/OC-little)

[Xjn's Blog](https://blog.xjn819.com/?author=1)

## 驱动列表
1. [Lilu.kext](https://github.com/acidanthera/Lilu)
2. [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen)
3. [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC)
4. [SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC)
5. [SMCSuperIO.kext](https://github.com/acidanthera/VirtualSMC)
6. [SMCBatteryManager.kext](https://github.com/acidanthera/VirtualSMC)
7. [SMCLightSensor.kext](https://github.com/acidanthera/VirtualSMC)
8. [AppleALC.kext](https://github.com/acidanthera/AppleALC)
9. [USBinjectAll.kext](https://github.com/RehabMan/OS-X-USB-Inject-All)
10. [CPUFriend.kext](https://github.com/acidanthera/CPUFriend)
11. [HibernationFixup.kext](https://github.com/acidanthera/HibernationFixup)
12. [NightShiftUnlocker.kext](https://github.com/0xFireWolf/NightShiftUnlocker)
13. [NVMeFix.kext](https://github.com/acidanthera/NVMeFix)
14. [ECEnabler.kext](https://github.com/1Revenger1/ECEnabler)
15. [VoodooPS2Controller.kext](https://github.com/acidanthera/VoodooPS2)
16. [BrightnessKeys.kext](https://github.com/acidanthera/BrightnessKeys)
17. [CpuTscSync.kext](https://github.com/acidanthera/CpuTscSync)
18. [NightShiftEnabler.kext](https://github.com/cdf/NightShiftEnabler)
19. [EnergyDriver.kext]
20. [NoTouchID.kext](https://github.com/al3xtjames/NoTouchID)
21. [RTCMemoryFixup.kext](https://github.com/acidanthera/rtcmemoryfixup)
22. [HoRNDIS.kext](https://github.com/jwise/HoRNDIS)


## 更新日志

### 2021年6月28日
1. 更新 OpenCore 到 0.7.0 版本
2. 更新 Kext驱动

### 2021年6月30日
1. 修复 触控板

### 2021年9月28日
1. 更新 OpenCore 到 0.7.3 版本
2. 将大部分驱动更新到 9月28日 编译版本
3. 兼容 macOS Monterey
4. 添加 Kext驱动
5. 更改 OpenCore 主题到 Auto
6. 删除蓝牙驱动（将蓝牙芯片替换成了BRCM94360CS2，如需蓝牙驱动请自行 百度/Google 搜索）
7. 删除 FakePCIID 全系驱动
