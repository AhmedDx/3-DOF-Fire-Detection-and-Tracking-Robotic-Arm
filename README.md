# 🔥 3-DOF Fire Detection and Tracking Robotic Arm

## 📌 Overview
This project presents the design and simulation of a **3-DOF robotic arm mounted on a mobile platform** for fire detection and tracking applications. The system integrates flame sensors with a control algorithm to detect fire direction and automatically orient the robotic arm toward the detected source.

The project is fully implemented and simulated using **MATLAB Simulink** and **Simscape Multibody**, providing a realistic environment for both control and mechanical modeling.

---

## 🎯 Features
- 🔥 Fire detection using multiple flame sensors  
- 🎯 Automatic direction tracking based on sensor input  
- 🤖 3-DOF robotic arm control  
- 📐 Inverse and forward kinematics implementation  
- 🔄 Smooth trajectory generation (circular motion)  
- ⚙️ Sensor-based control with enable/disable logic  
- 🧠 Intelligent base rotation using weighted averaging  
- 📊 Simulation in realistic physical environment (Simscape)  

---

## 🏗️ System Architecture
The system is designed as an integrated framework that combines sensing, decision-making, motion planning, and robotic control. The overall architecture enables the robotic arm to detect fire sources, determine their direction, and respond with accurate and smooth motion.


---

## ⚙️ Technologies Used
- MATLAB  
- Simulink  
- Simscape Multibody  

---


## 🧠 Key Concepts

### 🔹 Trajectory Generation
A circular trajectory is generated in Cartesian space.

### 🔹 Inverse Kinematics
Transforms desired position into joint angles.

### 🔹 Forward Kinematics
Validates end-effector position from joint angles.

### 🔹 Fire Controller
- Computes direction using sensor inputs  
- Generates `theta_offset`  
- Controls system activation using `enable`  

---

## ▶️ How to Run

1. Open MATLAB  
2. Navigate to the project folder  
3. Open the Simulink model
4. Run the Model
4. Run the simulation  

---

## 📊 Results
- Stable and smooth robotic motion  
- Accurate fire direction tracking  
- Reliable response under different sensor conditions  
- Realistic physical simulation using Simscape  

---

## 🚀 Future Work
- Real hardware implementation  
- Camera-based fire detection  
- Autonomous mobile navigation  
- Obstacle avoidance  
- AI-based fire localization  


---

## 👨‍💻 Author
Ahmed Mohammed Ahmed

---

## 📄 License
This project is for educational purposes.

