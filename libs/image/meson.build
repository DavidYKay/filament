src = [
  'src/ImageOps.cpp',
  'src/ImageSampler.cpp',
  'src/KtxBundle.cpp',
  'src/LinearImage.cpp',
  ]

#libimage = shared_library('image', src,

include_dirs = include_directories('include',
    )

depimage = declare_dependency(
  sources: src,
  include_directories : include_dirs,
  dependencies: [
    deputils,
    depmath,
  ],
  #link_with: libutils,
  #link_with: libutils,
  )

libimage = shared_library('image', src,
# TODO: include generate headers
  dependencies: [
    depimage,
    ],
  include_directories : include_dirs)
