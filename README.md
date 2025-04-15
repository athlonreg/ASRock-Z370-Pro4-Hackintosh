# ASRock Z370 Pro4 Hackintosh
Hackintosh EFI Bootloader for ASRock Z370 Pro4

## 详细配置

| 类型     | 配置                                                       |
| -------- | ---------------------------------------------------------- |
| 处理器   | 英特尔 Core i7-8700 3.2GHz 六核心十二线程                  |
| 主板     | 华擎 Z370 Pro4                                             |
| 内存     | 海盗船 DDR4 3200MHz 16GB x 2                               |
| 硬盘     | 三星 SM961 256GB、海康威视 C2000 Pro 1TB、西部数据蓝盘 2TB |
| 显卡     | 华擎 AMD Radeon RX Vega 56 8GB (已刷 Vega 64)              |
| 显示器   | 华硕 VG258QR 24.5寸 1080P 165Hz                            |
| 无线网卡 | Intel BE200                                                |
| 以太网卡 | Intel I219V + RTL8125 2.5G                                 |
| 声卡     | ALC892                                                     |



## BIOS

- 高级 -> CPU 配置 -> CFG Lock -- 关闭
- 高级 -> CPU 配置 -> Intel 虚拟化技术 -- 开启
- 高级 -> USB 配置 -> XHCI Hand-off -- Enabled
- 引导 -> 闪速启动 -- 关闭
- 引导 -> CSM(兼容性支持模块) -> CSM -- 关闭
- 高级 -> 芯片组配置 -> Above 4G Decoding -- 禁用(有核显的可以启用)
- 高级 -> 芯片组配置 -> VT-d -- 禁用(有核显的可以启用)
- 高级 -> 芯片组配置 -> IGPU 多监视器 -- 禁用(有核显的可以启用)
- 高级 -> 芯片组配置 -> 共享内存 -- 1024M(有核显的设置)

## 致谢

- wyhtc
- [vit9696](https://github.com/vit9696)
- [Acidanthera](https://github.com/acidanthera)
- [RehabMan](https://github.com/RehabMan)
- so on ...

