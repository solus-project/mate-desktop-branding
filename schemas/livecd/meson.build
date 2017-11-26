livecd_schemas = [
    'org.mate.caja.desktop.gschema.override',
    'com.solus-project.software-center.gschema.override',
]

custom_target('20_mate_settings_livecd.gschema.override',
    output: '20_mate_settings_livecd.gschema.override',
    capture: true,
    input: livecd_schemas,
    command: ['cat', '@INPUT@'],
    install: true,
    install_dir: path_schemadir,
)
