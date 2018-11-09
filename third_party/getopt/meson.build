# TODO: getopt build script


src = [
  'src/getopt.c',
  'src/getopt_long.c',
  ]

#libgetopt = shared_library('getopt', src,
depgetopt = declare_dependency(
  sources: src,
  # TODO: include generate headers
  #link_with: libutils,
  include_directories : include_directories(
    'include',
    ),
  )

#jsoncpp_dep = declare_dependency(
#  include_directories : jsoncpp_include_directories,
#  link_with : jsoncpp_lib,
#  version : meson.project_version(),
#  sources : jsoncpp_gen_sources)
