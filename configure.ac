#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([vdeplug4], [0.1], [info@v2.cs.unibo.it])
AM_INIT_AUTOMAKE([foreign dist-bzip2])
AC_CONFIG_SRCDIR([srcvdeplug4/vde_plug.c])
AC_CONFIG_HEADERS([include/config.h])
CFLAGS="$CFLAGS -Wall"
AC_ENABLE_SHARED(yes)
AC_ENABLE_STATIC(no)

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL

LT_INIT

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([fcntl.h stdint.h stdlib.h string.h unistd.h syslog.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_CHECK_FUNCS([strcmp])

AC_OUTPUT(
		[Makefile]
		[libvdeplug4/Makefile]
		[srcvdeplug4/Makefile]
		[include/Makefile]
		[man/Makefile]
		)
