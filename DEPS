# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'abbe466451ca975fecfdba453ef9073df52aefc5',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0d4ce028bf8b8a94d325dc1e1c20446153ba19c4',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4995a2f2723c401eb0ea3e10c81298906bf1422b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bd325d298442bd9d895f33f372bb16a976b7747f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '0c5928795a66e93f65e5e68a36d8daa79a209dc2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a59027c96db28b32a2c0a9cc8b858340620577e9',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '431f3b53ae73d91eb1560fef3862355d6345cd94',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '80de10c77b8d48896a395d1d5822181142569946',
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
