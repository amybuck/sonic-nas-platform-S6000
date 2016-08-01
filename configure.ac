#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([libsonic-nas-platform-s6000], [2.2.0], [support@dell.com])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([config.h.in])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_AWK
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
AC_PROG_RANLIB

LT_INIT([shared])

# Checks for libraries.
# FIXME: Replace `main' with a function in `-lsonic_common':
AC_CHECK_LIB([sonic_common], [main])
# FIXME: Replace `main' with a function in `-lsonic_cps_class_map':
AC_CHECK_LIB([sonic_cps_class_map], [main])
# FIXME: Replace `main' with a function in `-lsonic_logging':
AC_CHECK_LIB([sonic_logging], [main])
# FIXME: Replace `main' with a function in `-lsonic_object_library':
AC_CHECK_LIB([sonic_object_library], [main])

# Checks for header files.
AC_CHECK_HEADERS([string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T
AC_TYPE_UINT64_T

# Checks for library functions.

AC_CONFIG_FILES([Makefile
                 cfg/Makefile
                 src/Makefile])
AC_OUTPUT
