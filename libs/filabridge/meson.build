src = [
        'src/SamplerBindingMap.cpp',
        'src/SamplerInterfaceBlock.cpp',
        'src/UniformInterfaceBlock.cpp',
        'src/UibGenerator.cpp',
        'src/SibGenerator.cpp',
]
# TODO: fPIC

libfilabridge = shared_library('filabridge', src,
  include_directories : include_directories('include', 
    '../math/include',
    '../utils/include',
    ), 
  link_with: [libutils, 
    #libmath,
    ]
  )
