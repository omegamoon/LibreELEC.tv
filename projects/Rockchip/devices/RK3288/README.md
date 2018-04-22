# RK3288

This is a SoC device for RK3288

**Build**

| Modelname | Vendor and model |
| ------ | ------ |
| asus-tinkerboard | Asus Tinkerboard |
| mqmaker-miqi| MqMaker MiQi |

PROJECT=Rockchip ARCH=arm DEVICE=RK3288 DEVICE_MODEL=[Modelname] make image

**How to use on an Android device**
- Flash image to a sd-card
- Insert sd-card into the device
- Plug in power and LibreELEC should boot instead of Android
- Remove sd-card from device to boot into Android
