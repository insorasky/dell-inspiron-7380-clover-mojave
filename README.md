# dell-inspiron-7380-clover-mojave
DELL Inspiron 7380 Mojave Clover

### 我的本子配置：
- 型号：Dell Inspiron 7380
- CPU：Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz
- RAM：8GX2
- 显卡：Intel UHD Graphics 620 Kaby Lake Refresh 0x3EA0（仿冒UHD630 0x3E9B）
- 显示器：13.3"
- 分辨率：1920x1080
- 网卡：AC9260（使用Airportitlwm.kext驱动）
- 声卡：ALC295（懒得折腾AppleALC，VoodooHDA不是不能用）
- 硬盘：BC501 NVMe SK hynix 512GB

### 缺陷
- 自带HDMI接口有反应无输出，外置显卡HDMI可用

### BIOS配置项
- 关闭Secure Boot
- 关闭Intel VT-d
- 关闭Intel SGX

### 安装前注意
- 因为已经安装完毕，我把啰嗦模式关闭了，引导界面时间设为fast，在安装时建议将啰嗦模式打开并启用clover引导界面，以备调试。
