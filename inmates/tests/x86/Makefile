#
# Jailhouse, a Linux-based partitioning hypervisor
#
# Copyright (c) Siemens AG, 2013-2018
#
# Authors:
#  Jan Kiszka <jan.kiszka@siemens.com>
#
# This work is licensed under the terms of the GNU GPL, version 2.  See
# the COPYING file in the top-level directory.
#

include $(INMATES_LIB)/Makefile.lib

INMATES := mmio-access.bin mmio-access-32.bin

mmio-access-y := mmio-access.o

$(eval $(call DECLARE_32_BIT,mmio-access-32))
mmio-access-32-y := mmio-access-32.o

$(eval $(call DECLARE_TARGETS,$(INMATES)))
