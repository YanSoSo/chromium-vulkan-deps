# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '76b52ebf77833908dc4c0dd6c70a9c357ac720bd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'bccaa94db814af33d8ef05c153e7c34d8bd4d685',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '124a9665e464ef98b8b718d572d5f329311061eb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8714d7fad25c3af92f85f465b808740cfca6e85a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '450ead13e1064584da027d91192bd7bfb724640f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '4830af39dce87b415de1c99edbc3283844d38903',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d8188a974ccd08caffb5bd7fec58751e0c7d786',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a7c612e9cdef3f9cbd8ac284708d55201d523a4a',
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
