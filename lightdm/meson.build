lightdm_gtk_dir = join_paths(path_datadir, 'lightdm', 'lightdm-gtk-greeter.conf.d')
lightdm_dir = join_paths(path_datadir, 'lightdm', 'lightdm.conf.d')

install_data(
    '20_mate_config.conf',
    install_dir: lightdm_dir,
)

install_data(
    '20_mate_default.conf',
    install_dir: lightdm_gtk_dir,
)
