PKG_NAME = fdupes
PKG_VERS = 2.1.2
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/adrianlopezroche/$(PKG_NAME)/releases/download/v$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/ncursesw cross/pcre2

HOMEPAGE = https://github.com/adrianlopezroche/fdupes
COMMENT  = FDUPES is a program for identifying or deleting duplicate files residing within specified directories.
LICENSE  = MIT

# fdupes needs pcre2-32
ENV += PCRE2_CLI_FULL=1 

GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk
