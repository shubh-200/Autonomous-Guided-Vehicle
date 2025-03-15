
# Autonomous Guided Vehicle for a Restaurant Layout

This project aims to develop an Autonomous guided vehicle in the Gazebo simulator for a custom restaurant layout. The AGV is equipped with a LiDAR sensor which is visualized in the simulation world.  
A custom world is modelled to replicate a restaurant layout. Robot Operating System (ROS2) Humble LTS is used with Gazebo Classic.

## Software Stack
### 1. ROS2 Humble Hawksbill 
![Logo](https://docs.ros.org/en/humble/_static/humble-small.png) 

### 2. Gazebo Classic 
![Logo](https://gazebosim.org/assets/images/gazebo_horz_pos_topbar.svg)

### 3. Nav2 
![Logo](https://us1.discourse-cdn.com/flex022/uploads/ros/optimized/2X/7/781fa8ce870432b9682a95f855b315c454da87c7_2_138x250.png)



## Run Locally

1. Clone the project.

```bash
  git clone https://github.com/shubh-200/Autonomous-Guided-Vehicle
```

2. Make a ROS2 workspace.

```bash
  mkdir -p ros2_ws/src/agvrobot_description
```

3. Copy the contents of the project folder into agvrobot_description.

4. Build using colcon.

```bash
  cd ros2_ws
  colcon build
```

5. Source the underlay.

```bash
  source install/setup.bash
```

6. Run the launch file.

```bash
  ros2 launch agvrobot_description gazebo.launch.py
```

## Documentation

For more information on ROS2 Humble, follow this [documentation.](https://docs.ros.org/en/humble/index.html)

## Support

For support or collaboration, email shubhambargeofficial25@gmail.com.



