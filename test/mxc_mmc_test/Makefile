# list of platforms which did not want this test case
EXCLUDE_LIST:=

ifeq (,$(findstring $(PLATFORM), $(EXCLUDE_LIST)))
OBJS = $(OBJDIR)/autorun-mmc.sh $(OBJDIR)/autorun-mmc-blockrw.sh $(OBJDIR)/autorun-mmc-fdisk.sh $(OBJDIR)/autorun-mmc-mkfs.sh $(OBJDIR)/autorun-mmc-fs.sh
else
OBJS =
endif

all : $(OBJS)

.PHONY: clean
clean :
	rm -f $(OBJS)

#
# include the Rules
#
include ../make.rules

