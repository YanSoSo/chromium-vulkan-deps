# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '45405e1d942e7af1a1f2fad94a8b9ddf2600af0d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '3327924addfcffe8f1a4119cb09c1ad353fe1190',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29ba2493125effc581532518add689613cebfec7',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6b72fe20c5d261f9698a82742ae08d9930375981',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '63af1cf1ee906ba4dcd5a324bdd0201d4f4bfd12',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9f30d582eb82e2b3042ddec4973a4ce56e0b48d7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e60c43a479ce53c24588f621b6a9fb0ab9f6eff7',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd144944a1b5e907d4b5e5d9035fe4b250e1625f7',
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
