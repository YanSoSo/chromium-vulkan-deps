# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9290474dcfc7f9f872d3d14dd1dd54edc8a7cd8d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '345a7d171c43b9f79f27652d48b386578a70980a',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '92f21c9b214178ce67cf1e31a00a33312590403a',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7326b494d079cfd24d08e46e291754151e2b9462',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd594f70127b4198286b3472a48bee56e341259cd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0162d1648fa6452e4125fe3cc076998721622d1a',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7001f2eb37d151c5fec082e6b1a683cf7c6d85f9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5628f98978d312157dd49e7874ef8851cd18a423',
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
