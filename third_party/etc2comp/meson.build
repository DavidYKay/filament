src = [
  'EtcLib/Etc/Etc.cpp',
  'EtcLib/Etc/EtcMath.cpp',
  'EtcLib/Etc/EtcImage.cpp',
  'EtcLib/Etc/EtcFilter.cpp',
  'EtcLib/EtcCodec/EtcIndividualTrys.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_RGB8A1.cpp',
  'EtcLib/EtcCodec/EtcSortedBlockList.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_ETC1.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_R11.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_RGBA8.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_RGB8.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4Encoding_RG11.cpp',
  'EtcLib/EtcCodec/EtcBlock4x4.cpp',
  'EtcLib/EtcCodec/EtcDifferentialTrys.cpp',
]

depetclib = declare_dependency(
  sources: src,
  include_directories : include_directories(
    'EtcLib/Etc',
    'EtcLib/EtcCodec',
    ),
  )

