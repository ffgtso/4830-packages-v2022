include $(TOPDIR)/rules.mk

PKG_NAME:=ffgt-geolocate
PKG_VERSION:=3
PKG_RELEASE:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(TOPDIR)/../package/gluon.mk

define Package/ffgt-geolocate
  SECTION:=gluon
  CATEGORY:=Gluon
  DEPENDS:=+gluon-core +micrond
  TITLE:=Assist geolocating the node and survey the wifi spectrum
endef

define Package/ffgt-geolocate/description
	Provides WiFi based positioning in Config Mode
endef

$(eval $(call BuildPackageGluon,$(PKG_NAME)))
