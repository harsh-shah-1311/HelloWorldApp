#AC_PREREQ(2.60)

AC_INIT(HelloWorldApp,1.0,shahharsh1195@gmail.com)

AC_CONFIG_SRCDIR([HelloWorld.c])

AC_CONFIG_HEADER([config.h])

AM_INIT_AUTOMAKE(HelloWorldApp, main)

# Checks for programs

AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET

# Checks for library

AM_PROG_LIBTOOL

# Set Shared libraries

AC_DISABLE_STATIC
AC_ENABLE_SHARED

#AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
