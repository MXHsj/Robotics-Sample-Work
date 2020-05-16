## Video Description
1. ### File Name: object_searching_in _unknown_environment
   ### Description:
   The UGV (ClearPath Jackal) shown in the video started mapping in an unknown environment using the LIDAR mounted on top and searching for target objects using the kinect RGB-Depth camera. After locking on the target object, the robot drove their and took the object back to the initial position. The above process was repeated until no object can be found.

    ### Developing Environment:
    ROS + MATLAB

2. ### File Name:  remote_control_3D_object_construction
   ### Description:
   In this video, the operator (me) controls the 7-DOF Franka Emika robot manipulator with an Intel Realsense camera mounted on the end-effector and rotates about an object to obtain a point-cloud based 3D construction of the object. The robot is controlled in Cartesian space and collects one single frame of scan on the user's command. The frames are concatenated and displayed in real time.

   ### Developing Environment:
   Python + MATLAB for robot higher level (end-effector pose) control and point-cloud processing.
   C++ + ROS for robot lower level (end-effector velocity) control.
   
3. ### File Name: Swarm_final_1080p
   ### Description:
   This video shows 10 khepera robots traversing through a tunnel environment using cell-lattice formation. The formation control is achieved using Lennard-Jones potential field in a distributed manner. The group size is changing dynamically to maximize the area occupied by the swarm.
