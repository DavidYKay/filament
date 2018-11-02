src = [
        'src/ImGuiHelper.cpp',
]

material_srcs = [
  # TODO: run matc on this file
  'src/materials/uiBlit.mat',
  ]

# TODO: fPIC


shared_library('filagui', src,
# TODO: include generate headers
# TODO: link against imgui, filament, filamat
  include_directories : include_directories('include',
    '../../filament/include/'), 
  )
