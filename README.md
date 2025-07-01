🤖 5-DOF Welding Robot – Kinematic Modeling & Simulation

![image](https://github.com/user-attachments/assets/6064e07f-f151-4632-926a-ae4558f96e22)

This project presents the design, modeling, and kinematic analysis of a 5-degree-of-freedom (5DOF) anthropomorphic welding robot, developed using SolidWorks and analytical methods. The robot is intended for precise and flexible welding tasks in controlled industrial environments.

📘 Author: Bartosz Wojdon

🎓 Mechatronics Engineering, AGH University of Science and Technology


📌 Project Overview

✅ Full CAD model built in SolidWorks

✅ Forward and inverse kinematics formulated analytically

✅ Denavit-Hartenberg (DH) convention applied

✅ Numerical examples for specific joint angles and end-effector positions

✅ Mathematical modeling + SolidWorks simulation


Robot Structure
The robot has 5 rotational joints (DOF), designed to provide flexibility and reach for complex welding tasks. It was virtually constructed and analyzed using SolidWorks.


CAD Assembly & Parts

Modeled in SolidWorks

All six parts (base, arms, joints) designed individually Assembled and validated through virtual simulation

![image](https://github.com/user-attachments/assets/0d700a51-7dc4-4b42-b0ba-bb00f3cc907e)

![image](https://github.com/user-attachments/assets/5186a953-f16b-40eb-a3ea-ba5ead44f44f)

![image](https://github.com/user-attachments/assets/46b5e495-ab5f-4b4a-a930-37fb27708916)

![image](https://github.com/user-attachments/assets/10cc32fa-e6c2-4d98-8af4-0f55a48d2f7c)

![image](https://github.com/user-attachments/assets/083a2846-5aa4-4e67-bd84-b2559c8e47a5)

![image](https://github.com/user-attachments/assets/e341a49c-4dc2-44ce-9c7a-985229d648c7)


🧮 Kinematic Modeling
🔧 Denavit-Hartenberg Parameters

![image](https://github.com/user-attachments/assets/897dfce3-0951-4253-b3bf-4723d5312e49)

![image](https://github.com/user-attachments/assets/417bbe8c-30b5-4f3e-ab7f-c28eea30a145)


🔁 Forward Kinematics
![image](https://github.com/user-attachments/assets/bab3b3cb-2e1e-4320-906f-f2d3479817a9)

🔄 Inverse Kinematics

The inverse kinematics of the robot was thoroughly derived and documented in the attached PDF report.

Analytical solution is based on geometric decomposition.

Input: desired (x, y, z) coordinates.

Output: multiple valid joint angle configurations for θ₁–θ₄.

All solutions satisfy the wrist constraint:


| Tool                      | Purpose                                   |
| ------------------------- | ----------------------------------------- |
| **SolidWorks**            | Full 3D modeling and kinematic simulation |
| **Python/Math** (assumed) | Symbolic and numerical calculations       |
| **Trigonometry & DH**     | Kinematic modeling foundations            |
