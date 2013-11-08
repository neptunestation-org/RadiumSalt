AC_PREREQ([2.62])
AC_INIT([RadiumSalt], [0.9], [http://www.radiumsalt.org])
AM_INIT_AUTOMAKE([-Wno-portability])
AC_CONFIG_SRCDIR([src/org/radiumsalt/util/AutoTest.java])
AC_CANONICAL_HOST
AS_CASE([$host_os], [cygwin], [CYGPATH_PW="cygpath -pw"], [CYGPATH_PW="echo"])
AC_SUBST([CYGPATH_PW])
AC_CHECK_CLASSPATH
AC_PROG_JAVAC
AC_PROG_JAVA
AC_PROG_SED
AC_PROG_JAR
AC_PROG_INSTALL
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
