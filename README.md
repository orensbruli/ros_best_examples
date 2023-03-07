# ROS best examples
It's like an 'awesome' kind of repo but only with examples of code of ROS development

## Colcon

### [Debug of cmake ](https://github.com/ros2/rosidl_typesupport_fastrtps/issues/60)
```
colcon build --event-handlers console_direct+ --packages-select find_fastrtps_test --cmake-args --trace-expand --trace-source=/opt/ros/rolling/share/fastrtps_cmake_module/cmake/Modules/FindFastRTPS.cmake
```


## CMake
Examples for ROS packages (not only nodes)

### Ament
https://gist.github.com/dirk-thomas/83ae6bfbfc94e06cd519

### Ament auto
https://gist.github.com/dirk-thomas/a76f952d05e7b21b0128#file-cmakelists-txt

## CI/CD
### ROS packages to Debian packages workflow action
https://github.com/moveit/moveit2_packages/blob/main/.github/workflows/build.yaml

## Other useful file references

### The rosdep reference of packages:
When you are creating a ROS package and you don't know where to get the name of a dependence:
https://github.com/ros/rosdistro/blob/master/rosdep/base.yaml

If it's not a debian package you can look here:
https://github.com/ros/rosdistro/blob/master/rosdep/
