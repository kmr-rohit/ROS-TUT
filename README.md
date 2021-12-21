# ROS-TUT
The main purpose for this project to make you familiar with working on 2 wheeled robot 
using ros gazebo..

 initially you have to setup folders directory.
You can make folders as your wish but I suggest you to do as 
mine so that we can keep up with upcoming changes.

FOR DUAL BOOT INDIVIDUALS :
1. Create a folder named rostut (ROS - tutorial) in home and enter the same.
2. Create a folder named 2wheeledbot inside ROS-TUT.
3. Create a folder named simulation-ws ( workspace for simulating  bot) inside 2wheeledbot
4. Clone this repo here. <br>
   Steps:<br>
   A. open terminal <br>
   B. cd rostut/2wheeledbot/simulation_ws/. <br>
   C. git clone https://github.com/rk972006/ROS-TUT <br>
       Note: if get git error here : <code> 
sudo apt install git   </code> 
Use this command before processing with step C <br> 
5. rename ROS-TUT to src in simualtion_ws folder. <br>
6. Inside terminal (as left in step C) type the mentioned  command <code> catkin build </code> <br>
You will see a message build succesfull. <br>
  1.  Open a new terminal.
  2.  Input the following commands: <br>
<code> cd rostut/2wheeledbot/simulaion_ws</code><br>
   
       <code> source ./devel/setup.bash  </code><br>

       <code> roslaunch m2wr_description</code>
