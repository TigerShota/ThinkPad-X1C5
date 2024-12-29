## ThinkPad X1 Carbon Hackintosh

## OpenCore版本：1.0.3

## 系统版本：Sequoia_15.2

#### 已知适用型号

1. ThinkPad X1 Carbon(5th Gen)

图片展示

#### 硬件参数
| 硬件  | 名称       | 备注            |
|-----|----------|---------------|
| CPU | i5-7200U | Kaby Lake-U |
| GPU | Intel HD Graphics 620| FHD 1920x1080  |
| 内存 |  SK Hynix 4G*2   | LPDDR3-1866 Mhz   |
| 硬盘 | SAMSUNG MZVLW256HEHP | NVMe v1.2.0    |
| 网卡  | AC 8265    | 不支持隔空投送       |
| 声卡  |  Conexant CX8200  | 无 |
| 触控板 | PS2      | 支持多指触控和手势 |
| 摄像头 | Integrated Camera | 原厂摄像头 |

#### 已知问题

不工作：个人热点、USB共享网络、自动调节亮度、睡眠和休眠、指纹

#### 注意事项

1.  安装前请将Intel网卡驱动取消，并按照视频教程操作，否则无法进入系统或Intel网卡无法驱动。
    [B站教程视频](https://www.bilibili.com/video/BV1r5WyeyE3k) [OCLP-Mod](https://github.com/laobamac/OCLP-Mod/releases/tag/2.4.8)
2.  请不要将亮度调至最小值，否则显示器将黑屏。

#### BIOS说明

1.  请依据Hackintosh教程更改BIOS设置即可。

#### 早期版本
MacOS_Ventura_13.x版本：[Thinkpad_x1c5_i5-7200u_Ventura](https://www.lanzoux.com/iAxoO2jbqbqb)
