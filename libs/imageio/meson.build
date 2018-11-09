src = [
  'src/BlockCompression.cpp',
  'src/ImageDecoder.cpp',
  'src/ImageDiffer.cpp',
  'src/ImageEncoder.cpp',
  ]

shared_library('imageio', src,
# TODO: include generate headers
  dependencies : [
      dependency('libpng'),
      depimage,
  ],
  include_directories : include_directories('include',
    '../utils/include',
    '../math/include',
    #'../image/include',
    '../../third_party/tinyexr',
    '../../third_party/astcenc/include',
    '../../third_party/stb',
    '../../third_party/etc2comp/EtcLib/Etc',
    '../../third_party/etc2comp/EtcLib/EtcCodec',
    ), 
  # TODO: link against image math png tinyexr utils z astcenc stb EtcLib
  )
