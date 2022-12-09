# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6d8b00b1c6794dda092419700c2be40469bacdad',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'c77b09b57c27837dc2d41aa371ed3d236ce9ce47',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1d31a100405cf8783ca7a31e31cdd727c9fc54c3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9c6a925c87d4c6e203e440ecc8a57018e5bb8c4b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9b48e83ef8c318739f38a07e4cd15473ff09ad86',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b43758588be22f5a417320a085fa712a89159943',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'ffa89a44472a60d05705bbfb61ef8376babe9a34',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7348666a4514944758ff7bfc2ad7873efb463606',
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
