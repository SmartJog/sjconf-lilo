SUBDIRS = doc

EXTRA_DIST = confs templates plugins

SJCONF = @sjconf@

install-data-hook:
	$(SJCONF) --install-conf confs/lilo.conf
	$(SJCONF) --install-templates templates/lilo
	$(SJCONF) --install-plugin plugins/lilo.py
	$(SJCONF) --enable-plugin lilo
