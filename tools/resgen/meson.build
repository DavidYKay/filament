src = [
  'src/main.cpp'
  ]

deps = [
  deputils,
  depgetopt,
]

resgen = executable('resgen', src,
  #link_with: libs,
  dependencies: deps,
  include_directories: include_directories(
    '../../dummy'
    ),
  )
