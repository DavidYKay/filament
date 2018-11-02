src = [
  'src/BlockCompression.cpp',
  'src/ImageDecoder.cpp',
  'src/ImageDiffer.cpp',
  'src/ImageEncoder.cpp',
  ]

shared_library('imageio', src,
# TODO: include generate headers
  include_directories : include_directories('include'), 
  # TODO: link against image math png tinyexr utils z astcenc stb EtcLib
  )
