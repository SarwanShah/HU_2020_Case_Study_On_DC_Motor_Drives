# Power Electronics Application in DC Motor Drives

## Project Overview
This project was developed under the **EE-331 Electrical Machines** course at **Habib University** during Spring 2020. The project explores the application of **Power Electronics** in **DC Motor Drives**. It covers the design, control strategies, and MATLAB-Simulink modeling of motor drive circuits, including **AC to DC rectification** and **quadrant control** for industrial DC motors.

**REPORT: https://github.com/SarwanShah/HU_2020_Case_Study_On_DC_Motor_Drives/blob/main/Power%20Electronics%20Application%20in%20DC%20Motor%20Drives%20-%20Case%20Study%20-%20ss03595%20-%20Sarwan%20Shah.pdf**

**VIDEO PRESENTATION: **

<a href="https://www.youtube.com/watch?v=dFrL1lOqHpk" target="_blank">
    <img src="https://img.youtube.com/vi/dFrL1lOqHpk/maxresdefault.jpg" alt="Watch the video" width="400">
</a>


## Features  
- **AC to DC Rectification**  
  - Conversion of **3-phase AC** to **DC** using a **6-pulse rectifier**.
  - Improved power delivery with reduced I²R losses and smoothed output through filtering inductors.
  - Control using **thyristor-based gate firing** for dynamic control of power output.

- **Motor Control Strategies**
  - **1-Quadrant Control**: Basic motor speed control using adjustable firing angles.
  - **2-Quadrant Control**: Introduction of **dynamic braking** and **regenerative braking**.
  - **4-Quadrant Control**: Advanced full control over motor speed, torque, and braking, reducing reactive power consumption.

- **MATLAB-Simulink Model**
  - Demonstrates real-time behavior of DC motor drives with adjustable parameters.
  - Supports analysis of voltage, current, and power stress based on varying firing angles.

## Project Implementation  
### ➤ **AC to DC Rectification**  
- Utilizes a **3-phase, 6-pulse rectifier** circuit to ensure higher average DC voltage output.
- Integration of **filtering inductors** to maintain a steady current and reduce losses.

### ➤ **Thyristor Control**  
- **Thyristors** operate based on gate-firing principles to modulate power delivery.
- Gate pulses synchronized with AC phase for continuous conduction over 120°.

### ➤ **Quadrant Control**  
- **1-Quadrant Control**: Allows for acceleration and coasting with limited control over braking.
- **2-Quadrant Control**: Enables fast deceleration and reverse current flow for regenerative braking.
- **4-Quadrant Control**: Employs two converters for comprehensive speed, torque, and direction control.

### ➤ **MATLAB-Simulink Modeling**  
- Simulates real-world behavior of motor drives.
- Visualizes the impact of firing angles on voltage, current, and reactive power.

## ⚠ Design Challenges  
- High reactive power consumption at greater firing angles.
- Erratic motor behavior at lower speeds due to pulsating currents.
- Complexity and cost of implementing full 4-quadrant control.
3. Adjust firing angles to observe the effects on motor speed, torque, and reactive power.

## References  
- Wildi, T. *Electrical Machines, Drives, and Power Systems*. Pearson New International Edition, 2014.
- Various studies on **thyristor control** and **reactive power** generation.

