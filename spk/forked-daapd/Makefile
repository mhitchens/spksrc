SPK_NAME = forked-daapd
SPK_VERS = 25.0
SPK_REV = 1
SPK_ICON = src/transmission.png

DEPENDS = cross/busybox cross/$(SPK_NAME)

MAINTAINER = Matthew Hitchens
DESCRIPTION = stuff
DISPLAY_NAME = forked-daapd

HOMEPAGE = http://ejurgensen.github.io/forked-daapd/
LICENSE  = GPLv2

INSTALL_PREFIX = /usr/local/$(SPK_NAME)

INSTALLER_SCRIPT = src/installer.sh

BUSYBOX_CONFIG = usrmng
ENV += BUSYBOX_CONFIG="$(BUSYBOX_CONFIG)"

include ../../mk/spksrc.spk.mk
