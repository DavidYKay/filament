src = [
        'src/SamplerBindingMap.cpp',
        'src/SamplerInterfaceBlock.cpp',
        'src/UniformInterfaceBlock.cpp',
        'src/UibGenerator.cpp',
        'src/SibGenerator.cpp',
]
# TODO: fPIC

depfilabridge = declare_dependency(
  sources: src,
  include_directories : include_directories('include', 
    ), 
  dependencies: [
    deputils, 
    depmath, 
  ],
  link_with: [
    #libutils, 
    #libmath,
    ]
  )

#libfilabridge = shared_library('filabridge', src,
