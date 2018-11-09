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
      deptinyexr,
      depastcenc,
      #deputils,
      #depmath,
  ],
  include_directories : include_directories('include',
    '../../third_party/stb',
    '../../third_party/etc2comp/EtcLib/Etc',
    '../../third_party/etc2comp/EtcLib/EtcCodec',
    ), 
  # TODO: link against image math png tinyexr utils z astcenc stb EtcLib
  )
