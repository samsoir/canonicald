# Configuration file for autoconf to product configure

AC_INIT([canonicald], [0.1], [sam@def.reyssi.net])

#Build settings, ensures non-GNU complience
AM_INIT_AUTOMAKE([foreign -Wall -Werror])

#Checks for program
AC_PROG_RANLIB
AM_PROG_CC_C_O
AM_PROG_AR
AC_PROG_LIBTOOL

#Check for libraries

#Check for modules
PKG_CHECK_MODULES([CHECK], [check >= 0.9.4])

#Output files
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile src/Makefile tests/Makefile])

AC_OUTPUT
