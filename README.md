# Installing arduino robot arm on ROS steps
## 1.Install Virtual box
By following this link and choose the appropriate operating system
\n https://www.virtualbox.org/wiki/Downloads

## 2. Install Ubuntu 18.04 desktop image
By following the bellow link
https://releases.ubuntu.com/18.04/

## 3. Create virtual machine
Open virtual box
Click 'New' button to open a dialog.
Type a name for the new virtual machine.
Then click next until finish creating the vm
Start the new vm and choose the Ubuntu file that installed in step 2

## 4. Install ROS melodic 
Open Ubuntu terminal and follow the instruction in the bellow link
http://wiki.ros.org/melodic/Installation/Ubuntu
Configuring ROS Environment and Create ROS Workspace
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make

## 5. Install arduino_robot_arm in catkin_ws/src folder.

## 6. Install other packages like joint-state gazebo to control the motors and simulate the environment.

