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
    '../utils/include',
    '../math/include',
    '../filabridge/include',
    '../filamat/include',
    '../../filament/include',
    '../../third_party/imgui/include',
    ), 
  )
