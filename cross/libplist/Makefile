PKG_NAME = libplist
PKG_VERS = 2.0.0
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)                                                                              
PKG_DIST_SITE = http://www.libimobiledevice.org/downloads
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

HOMEPAGE = https://github.com/libimobiledevice/libplist
COMMENT  = A library to handle Apple Property List format in binary or XML
LICENSE  = https://raw.githubusercontent.com/libimobiledevice/libplist/$(PKG_VERS)/COPYING

GNU_CONFIGURE = 1

CONFIGURE_ARGS = --without-cython

include ../../mk/spksrc.cross-cc.mk
