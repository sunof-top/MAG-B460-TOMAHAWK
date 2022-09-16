# MAG-B460-TOMAHAWK

## EFI

- OpenCore: 0.8.3
- macOS version: 11.7
- macOS version: 12.6

## 硬件配置

| 组件 | 型号x                 |
| ---- | -------------------- |
| 主板 | MAG-B460-TOMAHAWK    |
| CPU  | Intel i5 10400       |
| 内存 | 芝奇 8GB * 2 3000MHz |
| 显卡 | 🈚️                    |
| SSD  | WD SN550 1TB         |
| 网卡 | 🈚️                    |

## 功能测试
- [x] 睡眠/唤醒
- [ ] Airdrop/Handoff/iMessage/FaceTime
- [x] 所有USB端口
- [ ] 核显硬件加速
- [ ] 蓝牙/WiFi
- [x] 声卡输出
- [ ] Sidecar

## Win+Mac双系统解决Win系统时间时差问题
在Windows下运行
```
Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
```
## 设置默认启动项

在启动选择界面，先选中要启动的项，然后按键盘的 Ctrl + Enter (回车键) 进入系统，下次重启后默认就选中该项了