# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '48a467b4136d24c29c79b661324e5fb5134a7709',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '12542fc6fc05000e04742daf93892a0b10edbe80',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '69155b22b3b1f2d0cfed48f59167d9792de1fd79',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '673d8bfcb6b1cd18977da539d8809237f7fb14e1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3df77fb3e4e0961f7f01de9a9ae20dfdcfc4910a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '121c1f42025a82dca7922a503ca77df51c37b394',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fedb3b8ed39899eeb7c549cd50a380132b9dc948',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1f33cbd222907eb6e6795a55c9859975609f66ba',
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
