mate_schemas = [
    'org.mate.background.gschema.override',
    'org.mate.interface.gschema.override',
    'org.mate.Marco.general.gschema.override',
    'x.dm.slick-greeter.gschema.override',
]

custom_target('20_mate_material.gschema.override',
    output: '20_mate_material.gschema.override',
    capture: true,
    input: mate_schemas,
    command: ['cat', '@INPUT@'],
    install: true,
    install_dir: path_schemadir,
)
