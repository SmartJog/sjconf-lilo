man8_MANS = sjconf-lilo.man 
DISTCLEANFILES = sjconf-lilo.man 
EXTRA_DIST = sjconf-lilo.t2t

SUFFIXES = .t2t

.t2t.man:
	txt2tags -o $@ $<
