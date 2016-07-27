# this file was copied directly from cisco_ucs/Makefile.am

MAINTAINERCLEANFILES	= Makefile.in

TARGET			= fence_powerman

SRC			= $(TARGET).py

EXTRA_DIST		= $(SRC)

sbin_SCRIPTS		= $(TARGET)

# No manpage yet
#man_MANS		= $(TARGET).8

# No tests defined yet
# FENCE_TEST_ARGS         = -l test -p test -a test -n 1

include $(top_srcdir)/make/fencebuild.mk
include $(top_srcdir)/make/fenceman.mk
include $(top_srcdir)/make/agentpycheck.mk
