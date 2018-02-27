# Plan B OpenWrt Config
Configuration for a TOR-ed accesspoint, Plan B style

# Build Instructions
Please follow the instructions in the OpenWrt [wiki](https://openwrt.org/docs/user-guide/additional-software/imagebuilder).

To use this config, please add the following make arguments:
 * FILES=${PATH_TO_THIS_REPO}/files
 * PACKAGES="-wpa_supplicant -ppp -ppp-mod-pppoe libustream-openssl tor iperf3 curl ca-certificates ca-bundle kmod-usb-storage kmod-fs-msdos kmod-fs-ext4 block-mount"
   
For help, please have a look at [build.sh](https://github.com/rettichschnidi/plan-b-imagebuilder) or create an issue.

# Known Good Hardware
* GL AR150
  * [GL.iNet](https://store.gl-inet.com/products/gl-ar150-mini-smart-router?variant=3092579975195)
  * [Amazon.com](https://www.amazon.com/GL-iNet-Pre-installed-Performance-Compatible-Programmable/dp/B01FJ4S9JK)
  * [Shenzhen linkedSmart Electronics Co.,Ltd](https://de.aliexpress.com/store/product/GL-iNet-GL-AR150-AR9331-Smart-WiFi-Wireless-Router150Mbps-Repeater-OPENWRT-Firmware-External-Internal-Antenna-Support/1946255_32673861702.html)
  * [Shenzhen HuaiYu Technology Ltd.](https://de.aliexpress.com/item/GL-iNet-AR-150-150Mbps-OPENWRT-Firmware-Mini-Routers-Wi-Fi-Router-WiFi-Repeater-Booster-Extender/32464052719.html)
  * [HoRiYeah](https://de.aliexpress.com/item/GL-iNet-GL-AR150-AR9331-150Mbps-WiFi-Wireless-Router-WiFi-Repeater-OPENWRT-Firmware-External-Internal-Antenna/32556315152.html)
