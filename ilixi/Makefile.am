## Makefile.am for /ilixi
SUBDIRS 									= 	core graphics lib types ui
INCLUDES 									= 	-I$(top_srcdir)/ilixi -Wall
lib_LTLIBRARIES 							= 	lib@PACKAGE@-@ILIXI_VERSION@.la
lib@PACKAGE@_@ILIXI_VERSION@_la_CPPFLAGS	=	@DEPS_CFLAGS@
lib@PACKAGE@_@ILIXI_VERSION@_la_LIBADD 		= 	@DEPS_LIBS@ \
												core/libilixi_core.la \
												graphics/libilixi_graphics.la \
												lib/libilixi_lib.la \
												types/libilixi_types.la \
												ui/libilixi_ui.la

lib@PACKAGE@_@ILIXI_VERSION@_la_SOURCES 	= 
lib@PACKAGE@_@ILIXI_VERSION@_la_LDFLAGS 	= 	-version-info $(LT_CURRENT):$(LT_REVISION):$(LT_AGE) -release $(LT_RELEASE)

ilixi_includedir							= 	$(includedir)/$(PACKAGE)-$(VERSION)
nobase_ilixi_include_HEADERS				= 	ilixiConfig.h ilixiGUI.h