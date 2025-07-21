# 5-DOF Robotic Arm Design using Onshape
![arm](arm.gif)

##  What is meant by “Degrees of Freedom (DOF)”?
**Degree of Freedom (DOF)** refers to the number of independent movements a robotic arm can perform.  
The image below shows different types of motion involved in a 5-DOF robotic arm:

![Degrees of Freedom](robot-interior.webp)

These include:
- **Revolve** – base rotation  
- **Forward and Backward** – linear segment motion  
- **Bend** – elbow-like joint movement  
- **Rotate** – twisting along the arm’s axis  
- **Swivel / Up and Down** – wrist-like adjustments


###  Joint Mechanisms
These motions are made possible using two main joint types:
- **Revolute Joint** – enables rotation around an axis  
- **Prismatic Joint** – enables linear sliding along an axis

![Joint Types](Joints.png)

## About Onshape

[Onshape](https://www.onshape.com/) is a 3D design (CAD) software that works directly in your browser.  
There’s also a downloadable version for desktop and mobile.

Why use it?
- Easy to learn for beginners  
- Free for students and hobby projects  
- No installation needed (works online)  
- Supports team collaboration

###  Recommended Tutorial Channels
**[Onshape Official Playlists](https://www.youtube.com/@OnshapeInc/playlists)** – official tutorials from Onshape, great for learning tools, features, and workflows step by step.

##  Arm Components

The robotic arm is made up of 6 main parts. The image below shows them separated for clarity:
![Parts](PartOfArm.png)

| Part # | Name                     | Description                                                  | Movement Type           |
|--------|--------------------------|--------------------------------------------------------------|--------------------------|
| 1️⃣     | Base (black + yellow)     | Rotates the whole arm around its axis (yellow is part of it) | Revolve                  |
| 2️⃣     | First Arm (blue)         | Moves up and down from the base                              | Revolute Joint           |
| 3️⃣     | Second Arm (blue)        | Adds additional bending motion                               | Revolute Joint           |
| 4️⃣     | Wrist Mount (gray)       | Connects to the gripper, may rotate                          | Optional Revolute Joint  |
| 5️⃣     | Gripper (red)            | End-effector to hold or grip objects                         | Fixed or Functional Grip |
