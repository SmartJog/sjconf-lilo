SUBDIRS = doc

EXTRA_DIST = confs templates plugins

install-data-hook:
	$(sjconf) --install-conf confs/lilo.conf
	$(sjconf) --install-template templates/lilo
	$(sjconf) --install-plugin plugins/lilo.py
	$(sjconf) --enable-plugin lilo
