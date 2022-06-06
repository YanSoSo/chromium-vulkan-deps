# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'adbf0d3106b26daa237b10b9bf72b1af7c31092d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '50b4d5389b6a06f86fb63a2848e1a7da6d9755ca',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b2a156e1c0434bc8c99aaebba1c7be98be7ac580',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c94501352d545e84c821ce031399e76d1af32d18',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3ef4c97fd6ea001d75a8e9da408ee473c180e456',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd3db2f78d9c12a607bb2c224a452535cf0ab780c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ef9db7a8ec52f6c56158d83f5d57ef388c1abec1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4fc8d5a14f10867a7552f8e36d6beadc13d4b6b1',
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
