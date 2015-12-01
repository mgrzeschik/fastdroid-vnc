bin_PROGRAMS = \
	fbvncserver

AM_CPPFLAGS = \
	-I$(top_srcdir)/include \
	-I$(top_builddir)/include
#	$(some_CFLAGS)

EXTRA_DIST = \
	autogen.sh

MAINTAINERCLEANFILES = \
	configure \
	aclocal.m4 \
	Makefile.in

#
# binary
#
fbvncserver_SOURCES = \
	fbvncserver.c

fbvncserver_LDADD = \
	-lvncserver
#	$(some_LIBS)

