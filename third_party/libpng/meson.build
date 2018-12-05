

# set(libpng_sources
#   ${libpng_public_hdrs}
#   pngdebug.h
#   pnginfo.h
#   pngpriv.h
#   pngstruct.h



src = [
  'png.c',
  'pngerror.c',
  'pngget.c',
  'pngmem.c',
  'pngpread.c',
  'pngread.c',
  'pngrio.c',
  'pngrtran.c',
  'pngrutil.c',
  'pngset.c',
  'pngtrans.c',
  'pngwio.c',
  'pngwrite.c',
  'pngwtran.c',
  'pngwutil.c',
]

deppng = declare_dependency(
        sources: src,
  dependencies : [
    deplibz,
  ],
  include_directories : include_directories('.'),
  )
