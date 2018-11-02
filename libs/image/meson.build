src = [
  'src/ImageOps.cpp',
  'src/ImageSampler.cpp',
  'src/KtxBundle.cpp',
  'src/LinearImage.cpp',
  ]

libimage = shared_library('image', src,
# TODO: include generate headers
  link_with: libutils,
  include_directories : include_directories('include',
    '../math/include',
    '../utils/include',
    ),
  )
