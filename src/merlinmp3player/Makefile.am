AM_CPPFLAGS = \
	@PYTHON_CPPFLAGS@ \
	-include Python.h

AM_CXXFLAGS = \
	-Wall \
	-fno-exceptions \
	@ENIGMA2_CFLAGS@ \
	@GSTREAMER_CFLAGS@ \
	@PTHREAD_CFLAGS@

plugindir = $(libdir)/enigma2/python/Plugins/Extensions/MerlinMusicPlayer

plugin_LTLIBRARIES = merlinmp3player.la

merlinmp3player_la_SOURCES = \
	merlinmp3player.cpp \
	merlinmp3player.h

merlinmp3player_la_LDFLAGS = \
	-avoid-version \
	-module \
	-shared

merlinmp3player_la_LIBADD = \
	@GSTREAMER_LIBS@
