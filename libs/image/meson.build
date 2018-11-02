src = [
  'src/ImageOps.cpp',
  'src/ImageSampler.cpp',
  'src/KtxBundle.cpp',
  'src/LinearImage.cpp',
  ]

libimage = shared_library('image', src,
# TODO: include generate headers
  include_directories : include_directories('include'), 
  link_with: libutils
  # TODO: link against math, utils
  )
