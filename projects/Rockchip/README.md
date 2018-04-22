# Rockchip

This project is for Rockchip SoC devices

## Devices

**RK3288**
Rockchip/devices/RK3288/models:
  * asus-tinkerboard     - Asus Tinkerboard
  * mqmaker-miqi         - MqMaker MiQi

**RK3328**
Rockchip/devices/RK3328/models:
  * box-z28              - Box-Z28
  * pine64-rock64        - PINE64 Rock64
                         - CloudMedia Popcorn Hour Transformer
  * pine64-rockbox       - CloudMedia Popcorn Hour RockBox
  * rikomagic-v3         - RikoMagic V3
  * ugoos-um4            - Ugoos UM4
  ! firefly-roc          - Firefly ROC-RK3328-CC

**RK3399**
Rockchip/devices/RK3399/models:
  * 96boards-rock960     - 96Boards ROCK960
  * vamrs-sapphire       - Vamrs Sapphire
  ! hardkernel-odroid-n1 - Hardkernel ODROID-N1
  ! pine64-rockpro64     - PINE64 RockPro64
  ! yundoo-y8            - Yundoo Y8
  ! rikomagic-mk39       - RikoMagic MK39
  ! ugoos-ut5pro         - Ugoos UT5 PRO

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
