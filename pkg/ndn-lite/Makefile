PKG_SOURCE_LOCAL ?= $(RIOTBASE)/../ndn-lite
PKG_BUILDDIR ?= $(PKGDIRBASE)/ndn-lite

.PHONY: all

all: git-download
	"$(MAKE)" -C $(PKG_BUILDDIR) -f $(CURDIR)/Makefile.ndn-lite

include $(RIOTBASE)/pkg/pkg.mk
