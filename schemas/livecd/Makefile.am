MATE_LIVE_SCHEMAS = \
	org.mate.caja.desktop.gschema.override \
	org.mate.panel.gschema.override

%.gschema.override:
	rm -f $@ ;
	for i in ${MATE_LIVE_SCHEMAS} ; do \
	    cat $${i} >> $@; \
	    echo  >> $@; \
	done ;

EXTRA_DIST = \
	$(MATE_LIVE_SCHEMAS)

overridesdir = \
	$(datadir)/glib-2.0/schemas

overrides_DATA = \
	20_mate_settings_livecd.gschema.override

distclean-local:
	rm -fv ${top_builddir}/schemas/livecd/20_mate_settings_livecd.gschema.override
