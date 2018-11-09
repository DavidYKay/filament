# TODO: build matc

src = [
  'src/matc/sca/ASTHelpers.cpp',
  'src/matc/sca/GLSLTools.cpp',
  'src/matc/sca/GLSLPostProcessor.cpp',
  'src/matc/Compiler.cpp',
  'src/matc/CommandlineConfig.cpp',
  'src/matc/Enums.cpp',
  'src/matc/JsonishLexer.cpp',
  'src/matc/JsonishParser.cpp',
  'src/matc/MaterialCompiler.cpp',
  'src/matc/MaterialLexer.cpp',
  'src/matc/ParametersProcessor.cpp',
  'src/matc/PostprocessMaterialCompiler.cpp',
  'src/matc/PostprocessMaterialBuilder.cpp',
  'src/main.cpp'
  ]


deps = [
  depgetopt,
  depfilamat,
  depfilabridge,
  deputils,
]

# target_link_libraries(${TARGET} matlang)

matc = executable('matc', src,
  # TODO: include generate headers
  #link_with: libs,
  dependencies: deps,
  include_directories : include_directories(
    'src/matc/',
    'src/matc/sca/',
    ),
  )
