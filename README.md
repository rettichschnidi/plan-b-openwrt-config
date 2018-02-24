# plan-b-openwrt-config
Configuration for a TOR-ed accesspoint, Plan B style

# Build Instructions
Please follow the instructions in the OpenWrt [wiki](https://openwrt.org/docs/user-guide/additional-software/imagebuilder).

To use this config, please add the following make arguments:
 * FILES=${PATH_TO_THIS_REPO}/files
 * PACKAGES="-wpa_supplicant -ppp -ppp-mod-pppoe libustream-openssl plan-b-tor iperf3 curl ca-certificates ca-bundle kmod-usb-storage kmod-fs-msdos kmod-fs-ext4 block-mount"
   
For help, please have a look at [build.sh](https://github.com/rettichschnidi/plan-b-imagebuilder) or create an issue.
