src = [
  'src/ChunkContainer.cpp',
  'src/ChunkInterfaceBlock.cpp',
  'src/TextDictionaryReader.cpp',
  'src/SpirvDictionaryReader.cpp',
  'src/MaterialChunk.cpp',
  'src/ShaderBuilder.cpp',
  'src/MaterialParser.cpp',
  'src/Unflattener.cpp',
]
# TODO: fPIC

shared_library('filaflat', src,
  dependencies: [ cc.find_library('dl') ],
  include_directories : include_directories('include',
    '../utils/include',
    '../filabridge/include',
    '../math/include',
    '../../third_party/robin-map/', 
    ), 
  )
