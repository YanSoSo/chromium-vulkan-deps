# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '581897f462f30c15cb9c024bb41d917b9aa64cc7',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': '97a438d214b24e4958ca137a18639670648cedd0',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ae217c17809fadb232ec94b29304b4afcd417bb4',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'eeb973f5020a5f0e92ad6da879bc4df9f5985a1c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e500c7c809f9a2acfa556bf0974456353759f0a5',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0cc98ec7acfbdbdbda4be79d5117cf04bda7eccf',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a956d1a0e57d825bb2dd03c74a8c79e84bf5cf48',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4898e4f27b6929e2db9f1a759c66d29cf3e9c1c6',
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
