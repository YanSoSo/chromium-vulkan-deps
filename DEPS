# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'adfcaba7ae7bac77037e68d7fb755efff3bae74c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'acf51c1b9f9f872b741ab369cb047898c9cc300b',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd790ced752b5bfc06b6988baadef6eb2d16bdf96',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1b3c4cb6855f7db1636985e1652ebbf91f81cd50',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9085224a1b45f78deadf94f800b0ec092d1c3568',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd34bfafff23602e857064bea6d99a35eb63f37f2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '3f141894d2d9e7edfc2fb5596af0cf3e23de9597',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b0c43ab09ccd795467b1dfb1a6bc55aad4aeaf8f',
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
