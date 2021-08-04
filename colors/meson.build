color_schemes_theme_dir = join_paths(get_option('prefix'), 'share/color-schemes')

# install yaru
if get_option('default')
  install_data('Yaru.colors', install_dir: color_schemes_theme_dir)
endif

# install yaru-dark
if get_option('dark')
  install_data('Yarudark.colors', install_dir: color_schemes_theme_dir)
endif
