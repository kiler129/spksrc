ARCH ?= braswell
TCVERSION ?= 6.2
PKG_NAME = braswell
PKG_BRANCH = 22259
PKG_ARCH = $(PKG_NAME)
PKG_EXT = txz
PKG_DIST_NAME = linux-3.10.x.$(PKG_EXT)
PKG_DIST_SITE = https://downloads.sourceforge.net/project/dsgpl/Synology%20NAS%20GPL%20Source/$(PKG_BRANCH)branch/$(PKG_ARCH)-source
PKG_DIST_FILE = $(PKG_NAME)-$(PKG_DIST_NAME)
PKG_EXTRACT = linux-3.10.x
SYNO_CONFIG = synoconfigs/$(ARCH)
BASE_ARCH = x86

HOMEPAGE = http://www.synology.com/

include ../../mk/spksrc.kernel-modules.mk
