# 🤖 5-DOF Welding Robot – Kinematic Modeling & Simulation

A complete design and analysis of an anthropomorphic **5-degree-of-freedom (5-DOF) welding robot**. The robot was modeled and simulated using **SolidWorks**, with full **kinematic analysis** (forward & inverse) based on the **Denavit-Hartenberg (DH)** convention.

> 📘 Author: **Bartosz Wojdon**  
> 🎓 Mechatronics Engineering, AGH University of Science and Technology

---

## 🧾 Project Highlights

✅ Full CAD model created in SolidWorks  
✅ Analytical forward and inverse kinematics  
✅ Denavit–Hartenberg (DH) parameter-based modeling  
✅ Numerical simulation and symbolic computation  
✅ Report and derivations included in PDF

---

## 🛠️ Robot Structure

The welding robot consists of **5 revolute joints**, offering high flexibility and precision. It was virtually designed for welding tasks in industrial applications with limited workspace.

### CAD Design:

- Modeled and assembled entirely in **SolidWorks**
- Six individual parts: base, arms, joints, gripper
- All components validated through **virtual simulation**

📸 CAD renders:

![Base](https://github.com/user-attachments/assets/0d700a51-7dc4-4b42-b0ba-bb00f3cc907e)  
![Assembly](https://github.com/user-attachments/assets/5186a953-f16b-40eb-a3ea-ba5ead44f44f)  
![Joints](https://github.com/user-attachments/assets/46b5e495-ab5f-4b4a-a930-37fb27708916)  
![Gripper](https://github.com/user-attachments/assets/10cc32fa-e6c2-4d98-8af4-0f55a48d2f7c)  
![Complete View](https://github.com/user-attachments/assets/083a2846-5aa4-4e67-bd84-b2559c8e47a5)  
![Welding Pose](https://github.com/user-attachments/assets/e341a49c-4dc2-44ce-9c7a-985229d648c7)

---

## 🧮 Kinematic Modeling

### 🔧 Denavit–Hartenberg Parameters

The robot's kinematics is fully described using the DH convention. The parameter table defines the transformation between each joint frame.

![DH Table](https://github.com/user-attachments/assets/897dfce3-0951-4253-b3bf-4723d5312e49)  
![Frame Assignments](https://github.com/user-attachments/assets/417bbe8c-30b5-4f3e-ab7f-c28eea30a145)

---

### 🔁 Forward Kinematics

Using homogeneous transformation matrices from the DH parameters, the pose of the end-effector is computed based on joint angles:

- Step-by-step symbolic matrix derivation
- Final transformation matrix calculated

📷 Example matrix output:

![FK Matrix](https://github.com/user-attachments/assets/bab3b3cb-2e1e-4320-906f-f2d3479817a9)

---

### 🔄 Inverse Kinematics

The inverse kinematics were derived **analytically** using geometric decomposition. The algorithm allows calculating possible joint angles for a given end-effector position.

- **Input**: Desired (x, y, z) position  
- **Output**: Valid sets of joint angles \( \theta_1 \) to \( \theta_4 \)  
- Multiple solutions satisfying the wrist constraint

Details and full derivation are included in the attached PDF.

---

## 🧰 Tools Used

| Tool              | Role                                        |
|------------------|---------------------------------------------|
| **SolidWorks**    | Full 3D modeling & simulation               |
| **Mathematics**   | Analytical kinematics (symbolic derivation) |
| **Python / Math** | Numerical validation (optional)             |
| **Trigonometry**  | Geometric approach in inverse kinematics    |

---

## 📄 Documentation

📎 All equations, diagrams, and derivations are included in the attached [engineering thesis PDF]((https://github.com/Bajtii/5DOF_Robot/blob/main/5DOF_Robot.pdf)).

---

## 📬 Contact

If you'd like to know more or reuse this model for your own simulation work, feel free to reach out via GitHub or LinkedIn.


