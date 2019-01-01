PKG_SOURCE_LOCAL ?= $(RIOTBASE)/../ndn-lite
PKG_BUILDDIR ?= $(PKGDIRBASE)/ndn-lite

.PHONY: all

all: git-download
	"$(MAKE)" -C $(PKG_BUILDDIR)

include $(RIOTBASE)/pkg/pkg.mk
