# Rockchip

This project is for Rockchip SoC devices

## Devices

| Device | Model |
| ------ | ------ |
| RK3288 | [Asus Tinkerboard](devices/RK3288/models/asus-tinkerboard) |
| | [MqMaker MiQi](devices/RK3288/models/mqmaker-miqi) |
| RK3328 | [Box-Z28](devices/RK3328/models/box-z28) |
|  | [PINE64 Rock64 / Cloudmedia Popcorn Hour Transformer](devices/RK3328/models/pine64-rock64)|
|  | [Cloudmedia Popcorn Hour RockBox](devices/RK3328/models/pine64-rockbox) |
|  | [RikoMagic V3](devices/RK3328/models/rikomagic-v3) |
|  | [Ugoos UM4](devices/RK3328/models/ugoos-um4) |
|  | [Firefly ROC-RK3328-CC](devices/RK3328/models/firefly-roc) |
| RK3399 | [96Boards ROCK960](devices/RK3399/models/96boards-rock960) |
|  | [Vamrs Sapphire](devices/RK3399/models/vamrs-sapphire) |
|  | [Hardkernel ODROID-N1](devices/RK3399/models/hardkernel-odroid-n1) |
|  | [PINE64 RockPro64](devices/RK3399/models/pine64-rockpro64) |
|  | [Yundoo Y8](devices/RK3399/models/yundoo-y8) |
|  | [RikoMagic MK39](devices/RK3399/models/rikomagic-mk39) |
|  | [Ugoos UT5 PRO](devices/RK3399/models/ugoos-ut5pro) |

**My single-board computer is not listed, will it be added in the future?**<br />
If your single-board computer uses a current generation SoC listed on http://opensource.rock-chips.com/wiki_Main_Page the odds are in your favor.

**My Android device is not listed, will it be added in the future?**<br />
You may have luck if your device vendor is open source friendly, otherwise keep using Android for best support.

## Links

* https://github.com/rockchip-linux
* http://opensource.rock-chips.com

## Useful debug commands

* `cat /sys/kernel/debug/dri/0/summary`
* `cat /sys/kernel/debug/dw-hdmi/status`
* `cat /sys/kernel/debug/clk/clk_summary`
* `hexdump -C /sys/class/drm/card0-HDMI-A-1/edid`
* `edid-decode /sys/class/drm/card0-HDMI-A-1/edid`
