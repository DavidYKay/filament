# Only linux, clang doesn't want to use a shared library that is not PIC.

# TODO: come back and support Windows and MacOS


#dependency('dl')
cc = meson.get_compiler('cpp',)

#compilerdeps   = declare_dependency(
#  dependencies : [
#    cc.find_library('dl')
#    ])

src = [
'src/BlueGLLinux.cpp',
'src/BlueGLCoreLinuxImpl.S',
]

# 'include'
    # set(CMAKE_CXX_FLAGS '${CMAKE_CXX_FLAGS} -fPIC')
shared_library('bluegl', src,
  dependencies: [ cc.find_library('dl') ],
  include_directories : include_directories('include'), 
  )
