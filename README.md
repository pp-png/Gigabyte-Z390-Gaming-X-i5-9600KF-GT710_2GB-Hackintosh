Gigabyte Z390 Gaming X and i5-9600K Hackintosh

硬件配置
类型	型号

主板	技嘉z390 Gaming X

CPU	i5-9600KF 6核6线程

显卡	 七彩虹GT710 2GB

内存	8+8+4+4=24GB DDR4 2666频率

无线网卡、蓝牙	  无

固态	西数M.2 500G SSD

电源	550W 模组

EFI 版本
OpenCore 0.6.3

SMBIOS ID
iMac19,1 / 27 寸

BIOS 配置

BIOS Q-Flash 升级为 10F
Advanced Mode > Settings > IO Ports > Initial Display Output > PCIe 1 Slot
Advanced Mode > Settings > IO Ports > Above 4G Decoding > Enabled
Advanced Mode > Settings > IO Ports > USB Configuration > XHCI Hand-off > Enabled
Advanced Mode > Boot > CSM Support > Disabled
Advanced Mode > Settings > IO Ports > Internal Graphics > Enabled
Advanced Mode > Settings > IO Ports > DVMT Pre-Allocated > 128M (此配置只在启用Internal Graphics后出现)
Advanced Mode > Power Management > ERP > Enabled
Boot > CFG Lock > Disabled
CFG 必须禁用才能启用 NVRAM
