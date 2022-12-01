# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a7603c132d0dd1476eb8e13e50d042820f2154a7',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c77b09b57c27837dc2d41aa371ed3d236ce9ce47',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1d31a100405cf8783ca7a31e31cdd727c9fc54c3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd9446130d5165f7fafcb3599252a22e264c7d4bd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2826791bed6a793f164bf534cd859968f13df8a9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3c25bbc5fa8551d5550773dd600c4b4f0b89a38a',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6361ae332cd31aaea0ef1494e2102e65b962afea',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7930b6705bd8f9bc573798b82aedc2ee917a72d5',
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
