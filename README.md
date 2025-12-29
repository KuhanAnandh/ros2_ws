Steps to run the Simulation:

Step1: 
  clone the repo in your ros2_ws or in any other workspace

Step2:
  source your workspace with

  source ~/ros2_ws/install/setup.bash

Step3:

  colcon build

Step4: 
  use the below given command to launch the Stonefish simulation.

  ros2 launch stonefish_ros2 stonefish_simulator.launch.py scenario_desc:=/home/kuhan/ros2_ws/src/stonefish_ros2/resources/scenes/floating_box.scn


  here change the directory according to your folders!!

Done. You will see box floating in Ocean.

