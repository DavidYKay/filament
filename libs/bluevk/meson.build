cc = meson.get_compiler('cpp',)

src = [
'src/BlueVK.cpp',
'src/BlueVKLinuxAndroid.cpp',
]

depbluevk = declare_dependency(
  sources: src,
  dependencies: [ 
      cc.find_library('dl'),
      #cc.find_library('pthread'),
      deputils, 
      ],
  include_directories : include_directories('include',
      #'../utils/include',
    ), 
  #link_with: [libutils, ]
  )

#libbluevk = shared_library('bluevk', dependencies: depbluevk)
