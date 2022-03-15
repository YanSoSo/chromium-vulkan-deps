# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '538231d8b46c22474a558671f89f80b25fcec72d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '565db34cba00171ded142e873b08fa9a24f0cec3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0e994ee9c4d4118ae56a7bdb4a7517b6443d2b81',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '0ab57c2c42a0029938139c72166aa67688cc080f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '384881cc90fe243b4d29bfbc359f59752c2be995',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ab207b0829a4ccd8c1bc2d47dc6c3c32afc4b7ca',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '99500cee1e2d343bd6905d6f0b63645fd161256a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd41543eb5210b53c4bb57a67d054d67bd57e4393',
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
