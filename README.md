# Instructions to launch the package
## View the robot

There are 3 different robot viewing modes, which are determined by 3 arguments: `use_xacro`, `use_gui`, and `use_robot_state_publisher`

The default view setting is set to:
```
    <arg name="use_xacro" default="false" />
    <arg name="use_gui" default="true" />
    <arg name="use_robot_state_publisher" default="true" />
````

This setting is used when the launch command is run without any arguments:
```
roslaunch navvis_description display.launch
```
1. `use_xacro`:

This determines if the xacro or the urdf file will be used to view the model

2. `use_gui`:

This determines if the joint_state_publisher GUI will be used to view the model

3. `use_robot_state_publisher`:

This determines if the robot_state_publisher will be used to view the model