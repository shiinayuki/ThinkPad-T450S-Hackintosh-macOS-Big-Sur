![关于本机](./Pic/ScreenShoot.jpg)
![触摸板](./Pic/trackpad.png)
![电池](./Pic/battery.png)
### 这是电脑的配置

- **Intel 5th Generation Architecture (Broadwell)**
- **Intel HD Graphics 5500**
- **Intel Series 9 Chipset Family**
- **macOS Big Sur**
- **Broadcom DW1560** 


### 推荐的**BIOS**设置
- `Security -> Security Chip`: **Disabled**;
- `Virtualization -> Intel Virtualization Technology`: **Enabled**;
- `Internal Device Access -> Bottom Cover Tamper Detection`:**Disabled**;
- `Anti-Theft -> Current Setting`: **Disabled**;
- `Anti-Theft -> Computrace -> Current Setting`: **Disabled**;
- `Secure Boot -> Secure Boot`: **Disabled**;
- `UEFI/Legacy Boot: UEFI Only;
CSM Support`: **Yes**.

### 注意！！
安装的时候需用`FakeSMC`，安装完成可以替换为`VirtualSMC`，可在`config,plist`中更改。
### 工作良好的地方

- CPU：变频良好。
- 显卡：HD5500，驱动良好，加速可用，可mini DP 外接显示器，有Dock的接HDMI显示器。
- 声卡：采用layout-id 32，若不合适，可自行更换。
- 触摸板：采用`VoodooSMBus`和`VoodooRMI`驱动，丝滑流畅。
- USB：驱动良好。
- 小红点：驱动良好。

### 不工作的地方
- VGA