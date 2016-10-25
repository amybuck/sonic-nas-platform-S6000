ACLOCAL_AMFLAGS=-I m4

cfgdir = $(sysconfdir)/sonic
cfg_SCRIPTS = cfg/*.xml

lib_LTLIBRARIES=libsonic_nas_platform.la

libsonic_nas_platform_la_SOURCES= src/nas_ndi_plat_stat.c

libsonic_nas_platform_la_LDFLAGS=-shared -lsonic_common -lsonic_logging -version-info 1:1:0

libsonic_nas_platform_la_CPPFLAGS=-D_FILE_OFFSET_BITS=64 -I$(includedir)/sonic

libsonic_nas_platform_la_CXXFLAGS=-std=c++11

