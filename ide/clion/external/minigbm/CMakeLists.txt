cmake_minimum_required(VERSION 3.6)
project(external_minigbm)
add_subdirectory(cros_gralloc/aidl/android.hardware.graphics.allocator-service.minigbm-x86_64-android)
add_subdirectory(cros_gralloc/mapper_stablec/mapper.minigbm-x86_64-android)
add_subdirectory(cros_gralloc/gralloc4/libminigbm_gralloc4_utils-x86_64-android)
add_subdirectory(libminigbm_gralloc-x86_64-android)