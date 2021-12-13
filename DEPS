# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ca1395120555b8f7c78a7ea5cd3676330f78623e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'e9cc6403341baf0edd430a4027b074d0a06b782f',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd53b49635b7484e86959608a65a64d8121e6a385',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ff07cfd86fa229525659f6b81058b3171a67bef1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e005e1f8175d006adc3676b40ac3dd2212961a68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ca9efe3f1ccd98a5fe05da71bf65087bcaa82f35',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '05c6171c04df6f3747f1c9ab6e7b50ef3256ac03',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9f537109da6db63f1caab817546c36db42f07cf5',
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
