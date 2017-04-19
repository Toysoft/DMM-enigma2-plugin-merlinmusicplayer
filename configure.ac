AC_INIT([enigma2-plugin-extensions-merlinmusicplayer],[4.3.0],[www.dreambox-tools.info])
AM_INIT_AUTOMAKE([foreign])

AM_SILENT_RULES([yes])

AC_USE_SYSTEM_EXTENSIONS
AC_SYS_LARGEFILE

AC_PROG_CXX
LT_INIT
AC_CONFIG_MACRO_DIR([m4])

AM_PATH_PYTHON
AX_PYTHON_DEVEL
AX_PTHREAD

PKG_CHECK_MODULES(ENIGMA2, enigma2)
PKG_CHECK_MODULES(GSTREAMER, gstreamer-1.0 gstreamer-pbutils-1.0)

AC_CONFIG_FILES([
Makefile
meta/Makefile
src/Makefile
src/images/Makefile
src/merlinmp3player/Makefile
])
AC_OUTPUT
