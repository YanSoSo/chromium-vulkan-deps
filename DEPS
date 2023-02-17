# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6d41bb9c557c5a0eec61ffba1f775dc5f717a8f7',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '4e2fdb25671c742a9fbe93a6034eb1542244c7e1',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aa331ab0ffcb3a67021caa1a0c1c9017712f2f31',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '69ed5adf108fbd9860f8bcab69b6e80767b8c5aa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'bd6443d28f2ebecedfb839b52d612011ba623d14',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '20154742948a43657bbeea5d4946d6e0a6ea65cb',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a2304cb131353df94812e8a0c537a101e82bf831',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a90644606866f8c80885c999135f822ac08433e9',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
