# RR-Manipulator-Kinematics-Simulators
A collection of Python-based simulators for a 2-DOF RR manipulator, including forward kinematics with slider control, a forward kinematics simulator driven by inverse kinematics solutions, and a dedicated inverse kinematics simulator. 
This repository contains interactive simulators for the 2-DOF RR (Revolute-Revolute) Manipulator, developed in Python with `matplotlib`.  
It provides three main modules for exploring forward and inverse kinematics in robotics:

🚀 Features
- Forward Kinematics (Slider-Controlled)
Adjust the joint angles using sliders to visualize the manipulator's configuration in real-time.



- Forward Kinematics (IK-Driven)  
Use joint angles computed from the inverse kinematics solver to control the manipulator.



- Inverse Kinematics Simulator 
Enter the equation of a curve on the User Interface to generate joint angles that position the manipulator’s end-effector.



 📂 Project Structure

RR-Manipulator-Kinematics-Simulators/

      FK_Simulator_for_RR_manipulator_with_Slider.py
 
      FK_Simulator_for_RR_Industrial_Robot.py
 
      IK_Generator_for_RR_manipulator_with_Simulator.py
 
      README.md

## 🛠 Requirements
- `Python 3.12`
- `numpy`
- `matplotlib`
- `tkinter`


▶️ Usage
Run any simulator with:

      FK_Simulator_for_RR_manipulator_with_Slider.py

      FK_Simulator_for_RR_Industrial_Robot.py

      IK_Generator_for_RR_manipulator_with_Simulator.py

🎯 Applications

      Educational tool for understanding the kinematics of serial manipulators.

      Useful for robotics students, researchers, and enthusiasts.

      A foundation for extending into dynamics, control, and trajectory planning.


📜 License
      This project is licensed under the MIT License.

👨‍💻 Developed by Afework Alemu

