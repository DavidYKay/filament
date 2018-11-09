project('filament', 'cpp', 'c',
  default_options : ['c_std=c11', 'cpp_std=c++14'])

add_global_arguments('-w', language: 'c++')
add_global_arguments('-w', language: 'c')

subdir('third_party')
#subdir('libs')

subdir('libs/utils')
subdir('libs/math')
subdir('libs/bluegl')
subdir('libs/bluevk')
subdir('libs/filabridge')
subdir('libs/filaflat')
subdir('libs/filamat')
subdir('libs/filamentjs')
subdir('libs/image')
subdir('libs/imageio')

subdir('tools')
subdir('filament')

subdir('libs/filameshio')
subdir('libs/filagui')

#  tools/matc/tools@matc@@matc@exe/src_matc_sca_GLSLTools.cpp.o 
# c++ -Itools/matc/tools@matc@@matc@exe -Itools/matc -I../tools/matc -I../tools/matc/src/matc/ -I../tools/matc/src/matc/sca/ -I../third_party/getopt/include -I../libs/filamat/include -I../libs/filamat/src/eiff -I../libs/filamat/src/shaders -I../libs/filamat/../utils/include -I../libs/filamat/../math/include -I../libs/filamat/../filaflat/include -I../libs/filamat/../filabridge/include -I../libs/filabridge/include -I../libs/filabridge/../math/include -I../libs/filabridge/../utils/include -I../libs/utils/include -I../libs/utils/../../third_party/robin-map/ -fdiagnostics-color=always -pipe -D_FILE_OFFSET_BITS=64 -Wall -Winvalid-pch -Wnon-virtual-dtor -std=c++14 -O0 -g  -MD -MQ 'tools/matc/tools@matc@@matc@exe/src_matc_sca_GLSLTools.cpp.o' -MF 'tools/matc/tools@matc@@matc@exe/src_matc_sca_GLSLTools.cpp.o.d' -o 'tools/matc/tools@matc@@matc@exe/src_matc_sca_GLSLTools.cpp.o' -c ../tools/matc/src/matc/sca/GLSLTools.cpp
# 
