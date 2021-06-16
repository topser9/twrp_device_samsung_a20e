# TWRP Samsung Galaxy A20e

# How to compile it:

How-to clone source and device tree:
```
$ mkdir -p ~/twrp && cd ~/twrp

$ repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
```
# Clone a20e repo
```
$ git clone https://github.com/topser9/twrp_device_samsung_a20e.git device/samsung/a20e
```
Sync
```
$ repo sync
```
# How-to build:
```
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_a20e-eng
$ mka recoveryimage
```
## How to find the image built
```
`$ cd /out/target/product/a20e`
```
see recovery.img
```
# Device Tree for Samsung Galaxy A20e (SM-A202F/K)

Device Tree Made by topser9
```
![Galaxy A20e](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a20e.jpg "Galaxy A20e")
## Specs
|        Component        |          Specification            |
| :---------------------- | :-------------------------------- |
| Chipset                 | Exynos 7884B                      |
| Memory                  | 3 GB                              |
| Storage                 | 32GB                              |
| Battery                 | 3000 mAh (non-removable)          |
| Dimensions              | 158.4 x 74.7 x 7.8 mm             |
| Display                 | 720 x 1560 pixels, 19.5:9, 268PPI |
| Release Date            | 2019 April                        |

