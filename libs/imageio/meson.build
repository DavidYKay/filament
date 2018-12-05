src = [
  'src/BlockCompression.cpp',
  'src/ImageDecoder.cpp',
  'src/ImageDiffer.cpp',
  'src/ImageEncoder.cpp',
  ]

shared_library('imageio', src,
# TODO: include generate headers
  dependencies : [
      #dependency('libpng'),
      deppng,
      depimage,
      deptinyexr,
      depastcenc,
      depetclib,
      #deputils,
      #depmath,
  ],
  include_directories : include_directories('include',
    '../../third_party/stb',
    ), 
  # TODO: link against image math png tinyexr utils z astcenc stb EtcLib
  )
