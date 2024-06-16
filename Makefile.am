SUBDIRS = src
dist_doc_DATA = README.md

install-exec-hook:
	setcap cap_dac_override,cap_sys_rawio=ep $(DESTDIR)$(bindir)/asus_tuf_ctl