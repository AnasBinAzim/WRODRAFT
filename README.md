<div align="center">
  <img src="https://github.com/user-attachments/assets/172c3a2a-33b5-4c01-a7e5-fbb2edcce263" alt="Mayerdoa Robotics Logo" width="200" />
</div>

# SMOKI: Autonomous Vehicle by Team MAYERDOA_ROBOTICS

This repository contains the engineering documentation for **SMOKI**, an autonomous vehicle developed by **Team MAYERDOA_ROBOTICS** for the **2024 WRO National Final (Future Engineers)** representing **Bangladesh**.

## Team Members

- **Anas Bin Azim** – [anas.azim.71@gmail.com](mailto:anas.azim.71@gmail.com)
- **Rakibul Islam** – [rakibul.rir06@gmail.com](mailto:rakibul.rir06@gmail.com)
- **Mohiuddin Sami** – [sm.mohiuddin.sami@gmail.com](mailto:sm.mohiuddin.sami@gmail.com)

## Repository Overview

- `models` – 3D printable files utilized in our robot.
- `getting started` – Guide to initiating the project.
- `src` – Main codebase for the robot.
- `video` – Link to a YouTube video showcasing our robot in action.
- `t-photos` – Team photographs (serious and candid).
- `v-photos` – Images of the robot from various angles.
- `others` – Additional essential photographs.

## Mechanical Design

### Mechanical Parts List

- M3 Nut 3mm – 10 pcs
- M3 15mm Screw – 12 pcs
- M2 Nut – 10 pcs
- 35.5mm Red Female-to-Female Round Spacer – 4 pcs
- 30mm Male-to-Female Hex Spacer – 4 pcs
- 15mm Male-to-Female Hex Spacer – 3 pcs
- Bearings

### Robot's Chassis

The **SMOKI** chassis is meticulously designed to balance functionality with aesthetics, incorporating:

- **Ackermann Steering System**: Ensures precise turns, reducing tire scrubbing and enhancing maneuverability by aligning the wheels to follow appropriate turning radii.
- **Bevel Gear Mechanism**: Efficiently manages torque and speed, providing precise control over movement with a compact and durable structure.
- **3D Printed Body**: Offers a sleek, customizable design, optimizing weight distribution and structural integrity through advanced 3D printing techniques.
- **Sonar Mounts**: Strategically positioned to maximize sensor performance, enhancing obstacle detection while seamlessly integrating into the chassis design.

## Electrical Design

### Electronics Parts List

- 25GA 800 RPM Motor
- Raspberry Pi 5 (8GB)
- SJCAM C200 Action Camera
- Arduino Nano
- Copper Plate
- MG90S Servo – 1 pcs
- Li-Ion Battery – 2 pcs
- Ultrasonic Sensor – 4 pcs
- 10A Buck Module
- MT3608 Booster Module
- L298N Motor Driver
- Push Button
- Buzzer

### Power Delivery and Optimization

Efficient power management is crucial for the robot's performance. We employed voltage conversion techniques to meet diverse power requirements:

- **LM4016 Buck Converter**: Steps down battery voltage from 8.4V to 5V, providing a stable supply for the Raspberry Pi 5, which demands 5-6A at peak performance.
- **MT3608 Boost Converter**: Steps up voltage to 14V, ensuring motors receive adequate current for smooth and responsive operation under varying loads.

### Raspberry Pi and Camera Integration

The **Raspberry Pi 5** powers the **SJCAM C200 Action Camera**, integral for navigation and obstacle detection. The optimized power delivery system ensures stable operation of the camera and other critical components.

## Integration of LEGO MINDSTORMS EV3 Expansion Set (45560)

To enhance the structural and functional capabilities of **SMOKI**, we integrated components from the **LEGO MINDSTORMS EV3 Expansion Set (45560)**. This set offers a wide range of supplementary elements, including unique structural pieces and mechanical components, facilitating advanced building and programming opportunities. The inclusion of these elements allowed us to:

- **Enhance Structural Integrity**: Utilize specialized beams and connectors to reinforce the chassis.
- **Improve Mechanical Functionality**: Incorporate gears and axles to refine movement mechanisms.
- **Streamline Sensor Integration**: Employ mounting elements for precise sensor placement.

**Why Use LEGO MINDSTORMS EV3 Expansion Set (45560)?**

The decision to incorporate the LEGO MINDSTORMS EV3 Expansion Set was driven by its versatility and compatibility with our design objectives. The set provides:

- **Diverse Components**: A variety of parts that support complex mechanical designs.
- **Ease of Assembly**: Modular pieces that facilitate quick prototyping and adjustments.
- **Educational Value**: Components designed for educational purposes, aligning with the WRO's emphasis on learning and innovation.

**Purchasing and Setup**

- **Purchase Link**: [LEGO MINDSTORMS EV3 Expansion Set (45560)](https://education.lego.com/en-us/product-resources/mindstorms-ev3/downloads/building-instructions/)
- **Building Instructions**: Detailed manuals are available on the [LEGO Education website](https://education.lego.com/en-us/product-resources/mindstorms-ev3/downloads/building-instructions/), providing step-by-step guidance for assembling various models.

## Conclusion

The integration of the LEGO MINDSTORMS EV3 Expansion Set (45560) into **SMOKI** exemplifies our commitment to leveraging high-quality, versatile components to enhance our robot's capabilities. This strategic choice aligns with the WRO's objectives of fostering innovation and education in robotics.

For more information on the LEGO MINDSTORMS EV3 Expansion Set, visit the [LEGO Education website](https://education.lego.com/en-us/product-resources/mindstorms-ev3/downloads/building-instructions/).



---

### Thank you for following our journey! We hope SMOKI inspires you to dream big and engineer even bigger! 💖🚀
