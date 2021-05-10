# baxter_simulation

#### 使用说明

1. 若要启动Baxter仿真器，可运行:  

$ roslaunch baxter_gazebo baxter_world.launch  

一旦启动，可运行以下命令:  

$ rosrun baxter_tools enable_robot.py -e  

这将产生响应: Robot Enabled.  

2. 运动示例:  

$ rosrun baxter_tools tuck_arms.py -t  
$ rosrun baxter_tools tuck_arms.py -u  

$ rosrun baxter_examples joint_velocity_wobbler.py  
