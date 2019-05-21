# Box2D CMake Support

This is a wrapper around the C++ library [Box2D](http://box2d.org/). The Source code can be found on [Github](https://github.com/erincatto/Box2D)

## Status

|                                        LICENSE                                         |                                                             Linux / macOS                                                             |                                                                         Windows                                                                         |                                    Issues                                     |
| :------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| [![License: Zlib](https://img.shields.io/badge/License-Zlib-lightgrey.svg)](./LICENSE) | [![Build Status](https://travis-ci.org/tobanteGaming/Box2D-cmake.svg?branch=master)](https://travis-ci.org/tobanteGaming/Box2D-cmake) | [![AppVeyor Build status](https://img.shields.io/appveyor/ci/tobanteGaming/Box2D-cmake.svg)](https://ci.appveyor.com/project/tobanteGaming/Box2D-cmake) | ![GitHub issues](https://img.shields.io/github/issues/tobanteGaming/Box2D-cmake.svg) |

## Usage

### Add as Submodule

```sh
cd $PROJECT_ROOT
git submodule add https://github.com/tobanteGaming/Box2D-cmake.git 3rd_party/Box2D-cmake
git submodule update --init --recursive
```

### Use

In CMakeLists.txt:

```
add_subdirectory(3rd_party/Box2D-cmake)
target_link_libraries(${PROJECT_NAME} tobanteGaming::Box2D)
```
