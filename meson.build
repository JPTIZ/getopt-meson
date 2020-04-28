project('getopt', 'c')

getopt = static_library(
  'getopt',
  files('getopt.c'),
)

getopt_dep = declare_dependency(
  link_with : getopt,
  include_directories : include_directories('.'),
)
