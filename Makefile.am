SUBDIRS = src data po

<<<<<<< HEAD
ACLOCAL_AMFLAGS = --install -I m4
=======
EXTRA_DIST = $(top_srcdir)/.version
BUILT_SOURCES = $(top_srcdir)/.version
$(top_srcdir)/.version:
	echo $(VERSION) > $@-t && mv $@-t $@
dist-hook:
	echo $(VERSION) > $(distdir)/.tarball-version
>>>>>>> 4a70069bc7d12d35bdc08f8286eb68d4e3420584
