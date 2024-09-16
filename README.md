# cmake-files
Collection of CMake files, used as a submodule in my Conan templates.

## Usage

Add the following to your main CMakeLists.txt after this repo has been added as a submodule.

```cmake
list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake-files/common/cmake")
include(snippets)
enable_clang_tidy()
enable_cppcheck()
```

```cmake
set_warnings(${PROJECT_NAME})
```
