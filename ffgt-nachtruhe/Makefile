include $(TOPDIR)/rules.mk

PKG_NAME:=ffgt-nachtruhe
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(TOPDIR)/../package/gluon.mk

define Package/ffgt-nachtruhe
  SECTION:=ffgt
  CATEGORY:=FFGT
  TITLE:=Luci module for nachtruhe settings
  DEPENDS:=+gluon-web-admin +ff-ap-timer
  MAINTAINER:=Freifunk KreisGT <info@freifunk-kreisgt.de>
endef

$(eval $(call BuildPackageGluon,$(PKG_NAME)))
