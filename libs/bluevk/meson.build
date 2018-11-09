
src = [
'src/BlueVK.cpp',
'src/BlueVKLinuxAndroid.cpp',
]

shared_library('bluevk', src,
  #dependencies: [ cc.find_library('dl') ],
  include_directories : include_directories('include',
    '../utils/include',
    ), 
  #link_with: [libutils, ]
  dependencies: [deputils, ]
  )
