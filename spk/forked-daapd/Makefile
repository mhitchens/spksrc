SPK_NAME = forked-daapd
SPK_VERS = 25.0
SPK_REV = 0
SPK_ICON = src/transmission.png

DEPENDS = cross/busybox cross/$(SPK_NAME)

MAINTAINER = Matthew Hitchens
DESCRIPTION = Linux/FreeBSD DAAP (iTunes) and MPD media server with support for AirPlay devices (multiroom), Apple Remote (and compatibles), Chromecast, Spotify and internet radio.
DISPLAY_NAME = forked-daapd

HOMEPAGE = http://ejurgensen.github.io/forked-daapd/
LICENSE  = GPLv2

INSTALL_PREFIX = /usr/local/$(SPK_NAME)

INSTALLER_SCRIPT = src/installer.sh

BUSYBOX_CONFIG = usrmng
ENV += BUSYBOX_CONFIG="$(BUSYBOX_CONFIG)"

include ../../mk/spksrc.spk.mk
