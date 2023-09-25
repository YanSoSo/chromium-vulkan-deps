# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2bfacdac91d5d9ba6bab7b4da52eb79c2300cd45',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '6e1fb9b09efadee38748e0fd0e6210d329087e89',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '79743b899fde5c954897b2694291002626358fac',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ee7598d49798e7bf34fabe55b5a438a381d450c8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'df60f0316899460eeaaefa06d2dd7e4e300c1604',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4f8c7962f4745d3a7126b5f31d58a42026369642',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '520163b4b3f3f6e4696a6355f029d9e05d3bb9cf',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '7ec2f4aa9ef807e11b61ea013c272352d647341a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a8d301301df3353d123653f9fd009d429a3ab5fd',
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

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
