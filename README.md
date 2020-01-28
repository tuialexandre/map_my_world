# map_my_world
Mapping of a simulated environment using RTAB-Map and C++ ROS nodes

## Launching Nodes

Launch the Gazebo world, RViz and the Robot:

```
roslaunch map_my_world world.launch
```

Now launch the teleop node:

```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

To launch the mapping node:


```
roslaunch <YOUR PACKAGE NAME> mapping.launch

```

## Viewing the Database

You can use the *rtabmap-databaseViewer* tool to explore and analyse your database:

```
rtabmap-databaseViewer ~/.ros/rtabmap.db
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
