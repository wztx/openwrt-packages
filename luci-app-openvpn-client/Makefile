# Copyright (C) 2021-2022 Lienol <lawlienol@gmail.com>

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-openvpn-client

LUCI_TITLE:=LuCI support for OpenVPN Client
LUCI_DEPENDS:=+openvpn-openssl +kmod-tun
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

chmod 0755 $(1)/etc/init.d/luci-app-openvpn-client

# call BuildPackage - OpenWrt buildroot signature
