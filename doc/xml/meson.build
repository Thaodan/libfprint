ent_conf = configuration_data()
ent_conf.set('PACKAGE', 'libfprint')
ent_conf.set('PACKAGE_BUGREPORT', 'https://gitlab.freedesktop.org/libfprint/libfprint/issues')
ent_conf.set('PACKAGE_NAME', 'libfprint')
ent_conf.set('PACKAGE_STRING', 'libfprint')
ent_conf.set('PACKAGE_TARNAME', 'libfprint-' + meson.project_version())
ent_conf.set('PACKAGE_URL', 'https://fprint.freedesktop.org/')
ent_conf.set('PACKAGE_VERSION', meson.project_version())
ent_conf.set('PACKAGE_API_VERSION', '1.0')
configure_file(input: 'gtkdocentities.ent.in', output: 'gtkdocentities.ent', configuration: ent_conf)
