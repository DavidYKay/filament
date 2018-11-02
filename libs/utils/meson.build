cc = meson.get_compiler('cpp',)

src = [
  'src/ashmem.cpp',
  'src/Allocator.cpp',
  'src/CallStack.cpp',
  'src/CString.cpp',
  'src/CountDownLatch.cpp',
  'src/CyclicBarrier.cpp',
  'src/EntityManager.cpp',
  'src/EntityManagerImpl.h',
  'src/JobSystem.cpp',
  'src/Log.cpp',
  'src/NameComponentManager.cpp',
  'src/Panic.cpp',
  'src/Path.cpp',
  'src/Profiler.cpp',
  'src/Systrace.cpp',
  'src/linux/futex.cpp',
  'src/linux/Path.cpp',
  ]

libutils = shared_library('utils', src,
# TODO: include generate headers
dependencies: [ 
  cc.find_library('c++') 
  #dependency('c++'),
  ],
  include_directories : include_directories(
    'include', 
    '../../third_party/robin-map/'), 
  # TODO: link against Threads
  )
