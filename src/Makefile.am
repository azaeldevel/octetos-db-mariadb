AUTOMAKE_OPTIONS=foreign 1.4


lib_LTLIBRARIES = liboctetos-db-maria.la

liboctetos_db_maria_la_CFLAGS = $(OCTETOS_DB_ABSTRACT_CFLAGS) $(LIBMARIADB_CFLAGS)
liboctetos_db_maria_la_LIBADD = $(OCTETOS_DB_ABSTRACT_LIBS) $(LIBMARIADB_LIBS)
liboctetos_db_maria_la_SOURCES = clientdb-maria.cc

octetos_db_includedir = $(includedir)/octetos/db
pkgconfigdir = $(libdir)/pkgconfig
octetos_db_include_HEADERS = clientdb-maria.hh
pkgconfig_DATA = octetos-db-maria.pc
EXTRA_DIST = octetos-db-maria.pc.in