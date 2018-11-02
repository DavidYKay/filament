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

shared_library('utils', src,
# TODO: include generate headers
  include_directories : include_directories('include'), 
  # TODO: link against Threads
  )
