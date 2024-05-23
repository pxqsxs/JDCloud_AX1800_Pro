# JDCloud_AX1800_Pro
winscp进入etc/opkg.conf文件
dest root /
dest ram /tmp
lists_dir ext /var/opkg-lists
option overlay_root /overlay
#option check_signature
注释最后一行取消软件包签名验证

软件包页面配置opkg换源
src/gz openwrt_base http://mirrors.pku.edu.cn/immortalwrt/snapshots/packages/aarch64_cortex-a53/base/
src/gz openwrt_luci http://mirrors.pku.edu.cn/immortalwrt/snapshots/packages/aarch64_cortex-a53/luci/
src/gz openwrt_packages  http://mirrors.pku.edu.cn/immortalwrt/snapshots/packages/aarch64_cortex-a53/packages/
src/gz openwrt_routing http://mirrors.pku.edu.cn/immortalwrt/snapshots/packages/aarch64_cortex-a53/routing/
src/gz openwrt_telephony http://mirrors.pku.edu.cn/immortalwrt/snapshots/packages/aarch64_cortex-a53/telephony/
