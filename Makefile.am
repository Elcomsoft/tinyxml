AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

nobase_dist_include_HEADERS = tinyxml.h

AM_CFLAGS = $(GLOBAL_CFLAGS)
AM_CXXFLAGS = $(AM_CFLAGS) $(GLOBAL_CXXFLAGS)
AM_LDFLAGS = $(libplist_LIBS)

lib_LTLIBRARIES = libtinyxml.la

libtinyxml_la_CFLAGS = $(AM_CFLAGS)
libtinyxml_la_CXXFLAGS = $(AM_CXXFLAGS)
libtinyxml_la_LDFLAGS = $(AM_LDFLAGS)
libtinyxml_la_SOURCES = 	tinystr.cpp \
													tinyxml.cpp \
													tinyxmlerror.cpp \
													tinyxmlparser.cpp

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = tinyxml.pc
