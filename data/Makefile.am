desktopdir = $(datadir)/applications
dist_desktop_DATA = fsearch.desktop

EXTRA_DIST = fsearch.desktop.in
CLEANFILES = fsearch.desktop

fsearch.desktop: fsearch.desktop.in
	$(AM_V_GEN) $(MSGFMT) --desktop --template $< -d $(top_srcdir)/po -o $@
