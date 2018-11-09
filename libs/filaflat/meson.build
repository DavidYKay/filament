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

depfilaflat = declare_dependency(
  sources: src,
  dependencies: [ 
    cc.find_library('dl'),
    deputils,
    depfilabridge,
    depmath,
    #deprobinmap,
    ],
  include_directories : include_directories('include',
      #'../utils/include',
      #'../filabridge/include',
      #'../math/include',
      '../../third_party/robin-map/', 
    ), 
  #link_with: [libutils, ]
  )
#shared_library('filaflat', src,
