src = [
  'src/MeshIO.cpp',
]

depfilameshio = declare_dependency(
    sources: src,
# TODO: include generate headers
# TODO: link against imgui, filament, filamat
  dependencies: [
      #deputils,
      #depmath,
      depfilabridge,
      depfilament,
  ],
  #link_with: [ libfilament ],
  include_directories : include_directories('include'), 
  )
#shared_library('filameshio', src,
