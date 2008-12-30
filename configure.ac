dnl Process this file with autoconf to produce a configure script.
    stat AC_INIT(sjconf-lilo, 0.1.0~dev)

dnl 2.52 is quite realistic
AC_PREREQ(2.52)

AM_INIT_AUTOMAKE([foreign])

dnl Default value for sjconf
default_sjconf=sjconf

AC_ARG_WITH([sjconf],
            [AS_HELP_STRING([--with-sjconf], [specifies path to sjconf binary])],
            [sjconf=$withval],
            [sjconf=$default_sjconf])

AS_IF([test "x$sjconf" = xno], [sjconf=true], [ : ])
AS_IF([test "x$sjconf" = xyes], [sjconf=$default_sjconf], [ : ])

AC_SUBST([sjconf])

AC_CONFIG_FILES([Makefile \
                 doc/Makefile \
                 plugins/lilo.py \
                 ])
AC_OUTPUT
