# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '90d4bd05cd77ef5782a6779a0fe3d084440dc80d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '131278458ea8eebe6a6e9c476fbcf71278726e1a',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6a55fade62dec6a406a5a721148f88a2211cbefa',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '940127a77d3ad795a4a1422fbeaad50c9f19f2ea',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b32da5329b50e3cb96229aaecba9ded032fe29cc',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9ec9ef8d177e96c8c92ad944117fcafcd2066633',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5f9e5f14e572a6c9f7ff4d54e2fd4d82632bc393',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5bc38a5238601a2998287e7c99cd23c17aed2671',
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
