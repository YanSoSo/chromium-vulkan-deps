# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2fb89a0072ae7316af1c856f22663fde4928128a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '0e2880ab990e79ce6cc8c79c219feda42d98b1e8',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '449bc986ba6f4c5e10e32828783f9daef2a77644',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ee30773650eca50b1cd3c913babcc2b50d7b91fd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c5b7a2fa18750e435e91e06a50cdc5451c5b9abd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '39dd126e16c7a1c7135265aae9ac67ae9e110db0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '58051062663477240484c8904459762ad544ba18',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9f65d3f73cab4a7a9a29865597876ba84cfba938',
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
