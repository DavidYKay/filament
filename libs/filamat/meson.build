

#set(HDRS
#        include/filamat/MaterialBuilder.h
#        include/filamat/Package.h)
#
#set(PRIVATE_HDRS
#        src/eiff/BlobDictionary.h
#        src/eiff/Chunk.h
#        src/eiff/ChunkContainer.h
#        src/eiff/DictionaryGlslChunk.h
#        src/eiff/DictionarySpirvChunk.h
#        src/eiff/Flattener.h
#        src/eiff/GlslChunk.h
#        src/eiff/LineDictionary.h
#        src/eiff/MaterialGlslChunk.h
#        src/eiff/MaterialInterfaceBlockChunk.h
#        src/eiff/MaterialSpirvChunk.h
#        src/eiff/ShaderEntry.h
#        src/eiff/SimpleFieldChunk.h
#        src/shaders/Shaders.h)


src = [
  'src/eiff/BlobDictionary.cpp',
  'src/eiff/Chunk.cpp',
  'src/eiff/ChunkContainer.cpp',
  'src/eiff/DictionarySpirvChunk.cpp',
  'src/eiff/LineDictionary.cpp',
  'src/eiff/MaterialSpirvChunk.cpp',
  'src/eiff/MaterialInterfaceBlockChunk.cpp',
  'src/eiff/SimpleFieldChunk.cpp',
  'src/shaders/CodeGenerator.cpp',
  'src/shaders/ShaderGenerator.cpp',
  'src/MaterialBuilder.cpp',
  ]


# TODO: fPIC

depfilamat = declare_dependency(
  sources: src,
  dependencies: [
      #deputils,
      #depmath,
      depsmolv,
      depfilaflat,
      depfilabridge,
],
# TODO: include generate headers
# TODO: link against imgui, filament, filamat
  include_directories : include_directories('include',
    # 'src/eiff',
    # 'src/shaders',
    'src',
    ), 
  )

# libfilamat = shared_library('filamat', dependencies: depfilamat)
