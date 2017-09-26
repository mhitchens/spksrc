PKG_NAME = avahi
PKG_VERS = 0.7
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)                                                                              
PKG_DIST_SITE = https://github.com/lathiat/avahi/releases/download/v$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/dbus cross/libdaemon

HOMEPAGE = http://www.avahi.org/
COMMENT  = Avahi is a system which facilitates service discovery on a local network via the mDNS/DNS-SD protocol suite.
LICENSE  = https://raw.githubusercontent.com/lathiat/avahi/v$(PKG_VERS)/LICENSE

GNU_CONFIGURE = 1

CONFIGURE_ARGS = --with-distro=none --disable-glib --disable-gobject --disable-qt3 --disable-qt4 --disable-gtk --disable-gtk3 --disable-gdbm --disable-pygobject --disable-python-dbus --disable-mono --disable-stack-protector

include ../../mk/spksrc.cross-cc.mk
