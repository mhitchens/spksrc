PKG_NAME = mxml
PKG_VERS = 2.10
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)                                                                              
PKG_DIST_SITE = https://github.com/michaelrsweet/mxml/releases/download/release-$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

HOMEPAGE = http://michaelrsweet.github.io/mxml/
COMMENT  = Tiny XML Library
LICENSE  = https://raw.githubusercontent.com/michaelrsweet/mxml/release-$(PKG_VERS)/COPYING

GNU_CONFIGURE = 1

CONFIGURE_ARGS = --prefix=$(STAGING_INSTALL_PREFIX)

include ../../mk/spksrc.cross-cc.mk
