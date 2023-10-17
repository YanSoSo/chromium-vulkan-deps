# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ebb0a8b28e5ea7a13146a24b3ad87b1966dbdfa3',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '2de1265fca722929785d9acdec4ab728c47a0254',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4183b260f4cccae52a89efdfcdd43c4897989f42',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5bb595091b3048d20afeb37a9a193350dccd607d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f4bfcd885214675a6a0d7d4df07f52b511e6ea16',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e0423d550ece88bdec05c1968cb9fd4bfa3f748b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f7017f23337b90a2b2ceb65a4e1050e8ad89e065',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '89b8b0df6de86957e9b3489ccfc953d9ec52bb68',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ee028c60f12191198d4dd60f12ceec4bc623c2f2',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
