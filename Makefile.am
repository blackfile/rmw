packextrasdir=@docdir@
SUBDIRS = src man test po
EXTRA_DIST = ABOUT-NLS README.md ChangeLog AUTHORS.md THANKS COPYING ReleaseNotes rmwrc.example

include aminclude_static.am

packextras_DATA=$(EXTRA_DIST)

ACLOCAL_AMFLAGS = --install -I build-aux/m4
