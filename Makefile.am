SUBDIRS = doc

EXTRA_DIST = confs templates plugins

all: plugins/lilo.py

install-data-hook:
	$(sjconf) --install-conf confs/lilo.conf
	$(sjconf) --install-template templates/lilo
	$(sjconf) --install-plugin plugins/lilo.py
	$(sjconf) --enable-plugin lilo

uninstall-hook:
	$(sjconf) --disable-plugin lilo
	$(sjconf) --uninstall-plugin lilo
	$(sjconf) --uninstall-template lilo
	$(sjconf) --uninstall-conf lilo
