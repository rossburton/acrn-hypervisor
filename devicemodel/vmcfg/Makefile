BASEDIR ?= ..

include $(BASEDIR)/vmcfg/scripts/kconfig/kconfig.mk
include ../../paths.make

all:

install:
	install -d $(DESTDIR)$(datadir)/acrn/samples/apl-mrb
	install -t $(DESTDIR)$(datadir)/acrn/samples/apl-mrb $(BASEDIR)/vmcfg/apl-mrb/mrb-env-setup.sh
