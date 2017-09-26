PKG_NAME = forked-daapd
PKG_VERS = 25.0
PKG_EXT = tar.xz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)                                                                              
PKG_DIST_SITE = https://github.com/ejurgensen/forked-daapd/releases/download/$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/libunistring cross/zlib cross/confuse cross/mxml cross/sqlite cross/libevent cross/libgcrypt cross/ffmpeg cross/avahi cross/libplist cross/libsodium cross/libantlr3c

HOMEPAGE = http://ejurgensen.github.io/forked-daapd/
COMMENT  = Linux/FreeBSD DAAP (iTunes) and MPD media server with support for AirPlay devices (multiroom), Apple Remote (and compatibles), Chromecast, Spotify and internet radio.
LICENSE  = https://raw.githubusercontent.com/ejurgensen/forked-daapd/25.0/COPYING

GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk
