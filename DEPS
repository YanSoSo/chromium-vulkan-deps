# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '06a7078ce74ab5c7801a165b8145859678831fb8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'cded61dde3f78a8d2a563a99501ac855b2e4ffab',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd13b52222c39a7e9a401b44646f0ca3a640fbd47',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bfd278617c3a7b59c0c4b33cdd0213ddfbb38d02',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ab48b9b20da5296c9d77756a3d8de4677d4c1fe2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4e1777a8ffbb9b2e784c09a82ecdbc10875825f0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6ef427d3b9877395e07f0618ada16d81c95ce974',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b5fcd77e31d034ac2fa97bc0da745ec10d83d11b',
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
