[![Build Status](https://travis-ci.org/tobanteGaming/Box2D-cmake.svg?branch=master)](https://travis-ci.org/tobanteGaming/Box2D-cmake)
[![License: Zlib](https://img.shields.io/badge/License-Zlib-lightgrey.svg)](./LICENSE)

# Box2D CMake Support

This is a wrapper around the C++ library [Box2D](http://box2d.org/). The Source code can be found on [Github](https://github.com/erincatto/Box2D)

## Usage
### Clone
In your project root:
```sh
git clone --recurse-submodules https://github.com/tobanteGaming/Box2D-cmake.git 3rdparty/Box2D-cmake
```
### Use 
In CMakeLists.txt:
```
add_subdirectory(3rd_party/Box2D-cmake)
target_compile_features(${PROJECT_NAME} PUBLIC cxx_std_17)
target_link_libraries(${PROJECT_NAME} TG::Box2D)
```


