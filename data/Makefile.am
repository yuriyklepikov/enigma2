SUBDIRS = countries fonts extensions keymaps skin_default rc_models lcd

dist_pkgdata_DATA = \
	encoding.conf \
	keymap.xml \
	menu.xml \
	prev.png \
	radio.mvi \
	black.mvi \
	rcpositions.xml \
	setup.xml \
	skin_default.xml \
	skin_subtitles.xml \
	skin.xml \
	startwizard.xml \
	freesat.t1 \
	freesat.t2 \
	unicable.xml

if HAVE_TEXTLCD
dist_pkgdata_DATA += skin_text.xml
else
if HAVE_COLORLCD
dist_pkgdata_DATA += skin_display96.xml
else
if HAVE_GIGABLUELCD
dist_pkgdata_DATA += skin_display220.xml
else
dist_pkgdata_DATA += skin_display.xml
endif
endif
endif
