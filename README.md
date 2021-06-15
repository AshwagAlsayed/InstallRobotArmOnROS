# Installing arduino robot arm on ROS steps
## 1.Install Virtual box
By following this link and choose the appropriate operating system
<br> https://www.virtualbox.org/wiki/Downloads

## 2. Install Ubuntu 18.04 desktop image
By following the bellow link
<br> https://releases.ubuntu.com/18.04/

## 3. Create virtual machine
Open virtual box
<br>Click 'New' button to open a dialog.
<br>Type a name for the new virtual machine.
<br>Then click next until finish creating the vm
<br>Start the new vm and choose the Ubuntu file that installed in step 2

## 4. Install ROS melodic 
Open Ubuntu terminal and follow the instruction in the bellow link
<br>http://wiki.ros.org/melodic/Installation/Ubuntu
<br>Configuring ROS Environment and Create ROS Workspace
<br>$ mkdir -p ~/catkin_ws/src
<br>$ cd ~/catkin_ws/
<br>$ catkin_make

## 5. Install arduino_robot_arm in catkin_ws/src folder.

## 6. Install other packages like joint-state gazebo to control the motors and simulate the environment.

