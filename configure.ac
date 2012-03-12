dnl Process this file with autoconf to produce a configure script.
AC_INIT(sjconf-lilo, 0.2.1~dev)

dnl 2.52 is quite realistic
AC_PREREQ(2.52)

AM_INIT_AUTOMAKE([foreign])

AC_PROG_SJCONF
AC_PATH_PROG(TXT2TAGS, txt2tags)

AC_CONFIG_FILES([Makefile \
                 doc/Makefile \
                 confs/Makefile \
                 plugins/lilo.py \
                 ])
AC_OUTPUT
