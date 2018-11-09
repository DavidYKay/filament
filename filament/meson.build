src = [
  #'src/components/CameraManager.cpp',
  #'src/components/LightManager.cpp',
  #'src/components/RenderableManager.cpp',
  #'src/components/TransformManager.cpp',
  #'src/driver/opengl/gl_headers.cpp',
  #'src/driver/opengl/OpenGLBlitter.cpp',
  #'src/driver/opengl/GLUtils.cpp',
  #'src/driver/opengl/OpenGLDriver.cpp',
  #'src/driver/opengl/OpenGLProgram.cpp',
  #'src/driver/CommandStream.cpp',
  #'src/driver/CommandBufferQueue.cpp',
  #'src/driver/CircularBuffer.cpp',
  #'src/driver/Driver.cpp',
  ##'src/driver/DriverAPI.inc',
  #'src/driver/Platform.cpp',
  #'src/driver/GPUBuffer.cpp',
  #'src/driver/Handle.cpp',
  #'src/driver/Program.cpp',
  #'src/driver/SamplerBuffer.cpp',
  #'src/Box.cpp',
  #'src/Camera.cpp',
  #'src/Color.cpp',
  #'src/Culler.cpp',
  #'src/DebugRegistry.cpp',
  #'src/DFG.cpp',
  #'src/VertexBuffer.cpp',
  #'src/Engine.cpp',
  #'src/Exposure.cpp',
  #'src/Fence.cpp',
  #'src/FrameInfo.cpp',
  #'src/FrameSkipper.cpp',
  #'src/Froxelizer.cpp',
  #'src/Frustum.cpp',
  #'src/IndexBuffer.cpp',
  #'src/IndirectLight.cpp',
  #'src/GpuLightBuffer.cpp',
  #'src/Material.cpp',
  #'src/MaterialInstance.cpp',
  #'src/PostProcessManager.cpp',
  #'src/PrecompiledMaterials.cpp',
  #'src/Renderer.cpp',
  #'src/RenderPass.cpp',
  #'src/RenderPrimitive.cpp',
  #'src/RenderTargetPool.cpp',
  #'src/Scene.cpp',
  #'src/ShadowMap.cpp',
  #'src/Skybox.cpp',
  #'src/SwapChain.cpp',
  #'src/Stream.cpp',
  #'src/Texture.cpp',
  #'src/UniformBuffer.cpp',
  #'src/View.cpp',
  #'src/Viewport.cpp',
]

#libfilament = shared_library('filament', src,
#  # TODO: include generate headers
#  #link_with: libutils,
#  include_directories : include_directories('include',
#    'src/components',
#    'src/details',
#    'src/driver',
#    'src',
#    #'../math/include',
#    #'../utils/include',
#    )
#  )

# TODO: Update matc flags
MATC_BASE_FLAGS = '-a all'
MATC_OPT_FLAGS  = ''
MATC_TARGET     = 'desktop'
#output_path     = '${GENERATION_ROOT}/generated/material/${localname}.inc'
#fullname        = get_filename_component("${mat_src}", ABSOLUTE)
output_path     = '/home/dk/Tools/vr/renderer/filament/src/out/generated/myfile.inc'
fullname        = '/home/dk/Tools/vr/renderer/filament/src/filament/src/materials/defaultMaterial.mat'

# run_command( 'matc', MATC_BASE_FLAGS, MATC_OPT_FLAGS, '-p', MATC_TARGET, '-m material', '-f header', '-o', output_path, fullname)
