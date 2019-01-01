PKG_SOURCE_LOCAL ?= $(RIOTBASE)/../ndn_standalone
PKG_BUILDDIR ?= $(PKGDIRBASE)/ndn_standalone

.PHONY: all

all: git-download
	"$(MAKE)" -C $(PKG_BUILDDIR)

include $(RIOTBASE)/pkg/pkg.mk
