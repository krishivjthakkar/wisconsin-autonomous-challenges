# ROS2 Merge Arrays

A ROS2 Humble package that merges two sorted integer arrays.

## Description
This node subscrbes to two topics publishing sorted arrays and publishes a merged sorted array.

**Subscribed Topics:**
- `/input/array1` (std_msgs/Int32MultiArray)
- `/input/array2` (std_msgs/Int32MultiArray)

**Published Topic:**
- `/output/array` (std_msgs/Int32MultiArray)

## Usage
```bash
ros2 run merge_arrays merge_arrays_node
```


## Build Instructions
```bash
cd ~/ros2_ws
colcon build --packages-select merge_arrays
source install/setup.bash
```
