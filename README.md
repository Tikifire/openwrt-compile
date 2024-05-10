# OpenWrt-Compile

自用，部署在GitHub Actions上的OpenWrt/LEDE编译

## 部署目标

目前部署的.config
| .config | 设备/架构 | 说明 |
|-------|-------|-------|
| rpi4 | 树莓派4B - bcm2711 | 为规避校园网，固定TTL、修改UA(UA2F)、修改IPID(RKP-IPID)、固定NTP |
| - | - | - |

## 致谢

感谢 [P3TERX - Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)，直接使用了这位大佬提供的GitHub Actions模板

感谢 [coolsnowwolf - lede](https://github.com/coolsnowwolf/lede)
