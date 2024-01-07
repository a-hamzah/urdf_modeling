
# Robot Modeling

Repository consists of multiple robot models being developed from scrach.

## Environment

ROS1 Noetic, Ubuntu 20.04


## Deployment

To deploy this project run

```bash
  mkdir -p catkin_ws/src
  cd colcon_ws/src
  git clone https://github.com/a-hamzah/robot_modeling.git
  rm -rf CMakeLists.txt
  cd ..
  catkin_make
```

Launch rviz

```bash
  roslaunch robot_model_pkg robot.launch
```
## Screenshots

![Screenshot from 2024-01-07 19-23-05](https://github.com/a-hamzah/urdf_modeling/assets/25130682/a3f183d5-87d8-4124-aed9-faaad3b98f59)

## Future Work

- Add joints and other links
