# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c0cf8ad87627227c7f1d3be6177bbf2832d3fc1b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '6d3518e23849326415129d275d2df40fe3fc6b64',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '87d5b782bec60822aa878941e6b13c0a9a954c9b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '272e4b3d07160254f2439f714d4c84f738e9dec6',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5177b119bbdf463b7b909855a83230253c2d8b68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3090fc12bd202eeb6792a59480a4217a250cb9a4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f7dff1f7dd68d636a7baff8eacbec38a352c0aca',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '92ed21f6a188b02dfc62a88c0ac40d5153429704',
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
