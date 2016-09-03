MATE_SCHEMAS = \
	org.mate.background.gschema.override \
	org.mate.font-rendering.gschema.override \
	org.mate.interface.gschema.override \
	org.mate.peripherals-mouse.gschema.override

%.gschema.override:
	rm -f $@ ;
	for i in ${MATE_SCHEMAS} ; do \
	    cat $${i} >> $@; \
	    echo  >> $@; \
	done ;

EXTRA_DIST = \
	$(MATE_SCHEMAS)

overridesdir = \
	$(datadir)/glib-2.0/schemas

overrides_DATA = \
	10_mate_settings.gschema.override

distclean-local:
	rm -fv ${top_builddir}/schemas/mate/10_mate_settings.gschema.override
