# Articubot One - Training Robot Build
**Diferential Drive Robot w/ Camera and Lidar**

Forked From: https://github.com/joshnewans/articubot_one (which is built from a template of his)

Updated to work with Jazzy (jazzy branch) and Gazebo Harmonic and Ubuntu 24.04

## Requirements
Computers and Related:
- Rasberry Pi 4 (or greater?) for robot
- Ardunio Nano for Motor Controller
- LiDaR (RP Lidar A1 was used here)
- Pi Camera compatible with your Pi
- Separate Dev machine with a bit more horse power than Pi
  
General:  
- Ubuntu 24.04 on Dev and Pi
- Ros2 Jazzy (see https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html)
- Ros2 GUI Tools/Rviz2 Etc. (sudo apt install ros-jazzy-desktop)

- Ros2 JSP (sudo apt install ros-jazzy-joint-state-publisher)
- Ros2 JSP GUI (sudo apt install ros-jazzy-joint-state-publisher-gui)
- Ros2 Xacro (sudo apt install ros-jazzy-xacro)
- Ros2 Teleop Twist Keyboard (sudo apt-get install ros-jazzy-teleop-twist-keyboard)
- Ros2 Teleop Joy (sudo apt-get install ros-jazzy-teleop-twist-joy)
- Ros2 Twist Mux (sudo apt install ros-jazzy-twist-mux)
- Ros2 Control (sudo apt install ros-jazzy-ros2-control)
- Ros2 Controllers (sudo apt install ros-jazzy-ros2-controllers)

Sim / Gazebo:
- Gazebo Harmonic (sudo apt install gz-harmonic ros-jazzy-ros-gz)
- Ros2 GZ Bridge (should be installed with Gazebo)

Robot:
- Josh's Ros2 Diff Drive Arduino HW Layer ([https://github.com/joshnewans/ros_arduino_bridge:Harmonic](https://github.com/joshnewans/diffdrive_arduino/tree/humble))
- Ros2 Twist Stamper (sudo apt install ros-jazzy-twist-stamper)

Nice to Have:
- Miniterm (sudo apt install python3-serial)
- Joystick Tools (sudo apt install joystick jstest-gtk evtest)
- Josh's Joystick Tester (https://github.com/joshnewans/joy_tester)

Misc Hardware (Not Extensive):
- Motors and wheels ([Amazon](https://www.amazon.com/Motor-Encoder-Mounting-Bracket-500RPM/dp/B0CKSYZS3J/ref=pd_hp_d_btf_rpt_sd_biaws_c_1?_encoding=UTF8&dd=AO2nbXNegJu67O816MvKYNNGzeC2M1AGI-JCm90QnS4%2C&ddc_refnmnt=free&pd_rd_i=B0CKSYZS3J&pd_rd_w=yGpom&content-id=amzn1.sym.9e463b6c-c9f7-426a-8ce6-80673aa5e801&pf_rd_p=9e463b6c-c9f7-426a-8ce6-80673aa5e801&pf_rd_r=25KCHPWS3TA4KD92YMWK&pd_rd_wg=3WLNT&pd_rd_r=f65ae34f-9aba-4b14-a5ed-dc15967ebdf6))
- One or more 5v DC-DC 1-2A buck converter ([Amazon](https://www.amazon.com/dp/B08NV3JCBC?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1))
- L298N Motor Driver or Better ([Amazon](https://www.amazon.com/dp/B07WS89781?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1))


