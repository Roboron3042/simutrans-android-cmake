cmake_minimum_required(VERSION 3.6)

project(SimutransAndroid)

# armeabi-v7a requires cpufeatures library
include(AndroidNdkModules)
android_ndk_import_module_cpufeatures()

add_subdirectory(SDL)
add_subdirectory(simutrans)
