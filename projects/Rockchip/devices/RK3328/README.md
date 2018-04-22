# RK3328

This is a SoC device for RK3328

**Build**

| Modelname | Vendor and model |
| ------ | ------ |
| box-z28 | Box-Z28 |
| pine64-rock64 | PINE64 Rock64 / Cloudmedia Popcorn Hour Transformer |
| pine64-rockbox | Cloudmedia Popcorn Hour RockBox |
| rikomagic-v3 | RikoMagic V3 |
| ugoos-um4 | Ugoos UM4 |
| firefly-roc | Firefly ROC-RK3328-CC |
| tchip-trn9 | T-Chip TRN9 |

PROJECT=Rockchip ARCH=arm DEVICE=RK3328 DEVICE_MODEL=[Modelname] make image

**How to use on an Android device**
- Flash image to a sd-card
- Insert sd-card into the device
- Plug in power and LibreELEC should boot instead of Android
- Remove sd-card from device to boot into Android
