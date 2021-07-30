# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'c94ec9356f1a12876ae959409ec67eddb8a90c16',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bab4e5911b1bfa5a86bc80006b7301ae48363844',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e7b49d7fb59808a650618e0a4008d4bae927e112',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5737dbb068da91274de9728aab8b4bf27c52f38d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b8c57b0a09f7324fec5a7c363f5e26ff4d5a3222',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '3aeed853ab6367bde74d3400ea3acad5bb2daa87',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ba8c4116410ddc8c90d44c3708435f098ef2b2f1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'de1a93015c18ca95acb400aafb1d44dd350c5607',
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
