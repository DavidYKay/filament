src = [
  'src/MeshIO.cpp',
]

shared_library('filameshio', src,
# TODO: include generate headers
# TODO: link against imgui, filament, filamat
  include_directories : include_directories('include',
    '../utils/include',
    '../math/include',
    '../filabridge/include',
    '../../filament/include/',
    ), 
  )
