sbin_PROGRAMS = hciattach_ivi

hciattach_ivi_SOURCES = hciattach_ivi.c hciattach.h \
	hciattach_st.c hciattach_ti.c hciattach_tialt.c

hciattach_ivi_LDADD = @BLUEZ_LIBS@

AM_CFLAGS = @BLUEZ_CFLAGS@

MAINTAINERCLEANFILES = Makefile.in \
        aclocal.m4 configure config.h.in \
	depcomp missing install-sh
