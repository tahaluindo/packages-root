include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-serverchan

PKG_MAINTAINER:=tty228 <tty228@yeah.net>

LUCI_TITLE:=LuCI support for serverchan
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+iputils-arping +curl +jq

define Package/$(PKG_NAME)/conffiles
/etc/config/serverchan
/usr/bin/serverchan/api/diy.json
/usr/bin/serverchan/api/logo.jpg
/usr/bin/serverchan/api/ipv4.list
/usr/bin/serverchan/api/ipv6.list
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
