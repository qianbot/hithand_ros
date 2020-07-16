# hithand_gazebo
## Introduction
This repo runs the gazebo simulation with robot model of Hithand.
## Directory layout

    .
    ├── hithand_description                   
    ├── ├── meshes                        # 3d models of dae, stl
    ├── ├── urdf                          # xacro, urdf and sdf files
    ├── ├── launch 
    ├── hithand_gazebo 
    ├── ├── launch 
    ├── ├── worlds
    ├── hithand_control  
    ├── ├── launch 
    ├── ├── config
    ├── Models                    # robot model file for inserting in gazebo
    ├── Experiments               #  folder for running experiment in Neurorobotic latform
    └── README.md
    

Contact:
qian.feng@tum.de

## To Run
```
cp -r hithand_description hithand_control hithand_gazebo /path/to/catkin_ws/src 
cd /path/to/catkin_ws 
catkin_make 
```
