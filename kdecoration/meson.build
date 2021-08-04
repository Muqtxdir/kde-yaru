aurorae_theme_dir = join_paths(get_option('prefix'), 'share/aurorae/themes')

# install yaru
if get_option('default')
  install_subdir('org.kwin.aurorae.yaru', install_dir: aurorae_theme_dir)
endif

# install yaru-dark
if get_option('dark')
  install_subdir('org.kwin.aurorae.yaru.dark', install_dir: aurorae_theme_dir)
endif
