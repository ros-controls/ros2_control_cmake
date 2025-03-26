# ros2_control_cmake

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This package provides CMake macros and is a part of the ros2_control framework.
For more, please check the [documentation](https://control.ros.org/).

## Usage
Add it as build dependency in your `package.xml`

```xml
<build_depend>ros2_control_cmake</build_depend>
```

and add the provided macros to the `CMakeLists.txt` file

```cmake
find_package(ros2_control_cmake REQUIRED)
set_compiler_options()
export_windows_symbols()
```

## Build status

| Distribution | Repository Link | Build Status |
|--------------|-----------------|--------------|
| Humble      | [master](https://github.com/ros-controls/ros2_control_cmake/tree/master) | not created yet |
| Jazzy     | [master](https://github.com/ros-controls/ros2_control_cmake/tree/master) | [![Jazzy Build](https://github.com/ros-controls/ros2_control_cmake/actions/workflows/jazzy-build.yml/badge.svg?branch=master)](https://github.com/ros-controls/ros2_control_cmake/actions/workflows/jazzy-build.yml) |
| Rolling     | [master](https://github.com/ros-controls/ros2_control_cmake/tree/master) | [![Rolling Build](https://github.com/ros-controls/ros2_control_cmake/actions/workflows/rolling-build.yml/badge.svg?branch=master)](https://github.com/ros-controls/ros2_control_cmake/actions/workflows/rolling-build.yml) |
