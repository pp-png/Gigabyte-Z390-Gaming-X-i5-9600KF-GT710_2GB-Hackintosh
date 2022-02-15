Gigabyte Z390 Gaming X and i5-9600KF Hackintosh

# 系统
Big Sur 11.1 ➕win10

# 硬件配置

主板	技嘉z390 Gaming X

CPU	i5-9600KF 6核6线程

显卡	 七彩虹GT710 2GB

内存	8+8+4+4=24GB DDR4 2666频率

无线网卡、蓝牙	  无

固态	西数M.2 500G SSD ➕ SATA 512GB

电源	550W 模组

# EFI 版本
OpenCore 0.6.3

# SMBIOS ID
iMac19,1 / 27 寸

# BIOS 配置

BIOS Q-Flash 升级为 10F

Advanced Mode > Settings > IO Ports > Initial Display Output > PCIe 1 Slot

Advanced Mode > Settings > IO Ports > Above 4G Decoding > Enabled

Advanced Mode > Settings > IO Ports > USB Configuration > XHCI Hand-off > Enabled

Advanced Mode > Boot > CSM Support > Disabled

/#  Advanced Mode > Settings > IO Ports > Internal Graphics > Enabled                                                   #

/# Advanced Mode > Settings > IO Ports > DVMT Pre-Allocated > 128M (此配置只在启用Internal Graphics后出现)                #

“/#”标注的 没核显不用管（cpu后面带F的表示没核显）
Advanced Mode > Power Management > ERP > Enabled

Boot > CFG Lock > Disabled
CFG 必须禁用才能启用 NVRAM


# 目前工作正常

cpu变频 ok

睡眠 OK

声卡 OK

显卡 OK （HDMI、DVI、VGA均已驱动）

有线网卡 OK

USB3.0、2.0 均正常





