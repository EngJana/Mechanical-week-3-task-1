# Mechanical Week 3 Task 1

Smart Methods Internship - Mechanical Discipline

## Robot Arm Assembly and Control

This project involves the creation of a 5 DoF robot arm using Blender for 3D modeling

## Creating the Robot Arm Using Blender

### Generate the Robot Arm Shapes:

1. **Cylinders for Bases and Arm Joints**
2. **Cubes for Arm Links**

### Adjusting the Shapes:

Using Blender tools and modifiers to adjust the links and joints measurements and prepare them for motor placement:

- **Move:** Positioning and placing each link and joint to create the arm.
- **Rotate:** Adjust the links and joints to the desired orientation.
- **Scale:** Modify the lengths of the arm segments along each axis.
- **Bevel Modifier:** Smooth the edges of the arm.

<img width="346" alt="m1" src="https://github.com/user-attachments/assets/94c38e5f-09bc-4ce6-8b4e-bc815addb279">

### Detailed Creation Process:

After generating the basic shapes (cylinders and cubes), the following steps were taken to create the robot arm as shown in the image:

1. **Positioning the Base:**
   - A cylinder was used for the base of the arm. It was scaled to the appropriate size to provide a stable foundation.

2. **Creating Arm Joints:**
   - Smaller cylinders were added for the joints. These cylinders were positioned at the connection points between the arm segments.

3. **Connecting Arm Links:**
   - Cubes were used to create the arm links. Each cube was scaled to the desired length and positioned between the joints.
   - The cubes were then rotated to align properly with the joints and ensure smooth movement.

4. **Adjusting the Joints and Links:**
   - The `Move` tool was used to position each joint and link accurately.
   - The `Rotate` tool was used to orient the joints and links in the correct direction.
   - The `Scale` tool was used to adjust the dimensions of the links, ensuring that each segment was proportional.

5. **Smoothing the Edges:**
   - The `Bevel Modifier` was applied to the edges of the arm links and joints to smooth out sharp corners, giving the arm a more refined appearance.

6. **Final Assembly:**
   - The individual components (base, joints, and links) were assembled together by precisely positioning each part to create a cohesive robot arm structure.

## Animation

### Steps to Animate the Robot Arm:

1. **Add Armature:**
   - Go to `Add > Armature`.

2. **Position Armature:**
   - Switch to `Edit Mode` and adjust the bones to fit inside your character model. Ensure all major joints align correctly.
  
     <img width="286" alt="m2" src="https://github.com/user-attachments/assets/ba88a4c4-5560-4f31-9621-f21034f6974b">

3. **Parent Armature to Mesh:**
   - Select the character mesh, then `Shift + Select` the armature.
   - Press `Ctrl + P` and choose `With Automatic Weights` to automatically assign weights based on proximity.

4. **Adjust Weights:**
   - Switch to `Weight Paint` mode to fine-tune the weights of the vertices for each bone, ensuring smooth and accurate deformations.

5. **Add Animation:**
   - With the armature selected, switch to `Pose Mode`.
   - Create keyframes by pressing `I` and selecting the type of transformation (e.g., Location, Rotation).

6. **Animate:**
   - Move the timeline slider and adjust the pose of the character. Insert keyframes at different points to create the desired animation sequence. Press `A` then `I`.

7. **Playback and Adjust:**
   - Play back the animation using the timeline to check for any issues. Adjust keyframes and weight painting as necessary to improve the animation.

robot 5 DoF movement 
- initial state
<img width="582" alt="m3" src="https://github.com/user-attachments/assets/ad01567e-1ac0-4ca4-a314-3ab5b31bac41">
- base move
<img width="578" alt="m4" src="https://github.com/user-attachments/assets/ebf2deed-51a6-4c7b-a829-f58e459b5c6f">
- lower arm move
<img width="581" alt="m5" src="https://github.com/user-attachments/assets/7b32dd90-5bd8-4cb7-9968-899f5685074e">
- middle arm move
<img width="583" alt="m6" src="https://github.com/user-attachments/assets/b6aa261e-30e5-4844-9f36-52fcda125d5e">
- higher arm move
<img width="581" alt="m7" src="https://github.com/user-attachments/assets/4af3661a-6333-4b9f-a0f1-6805e60b331b">
- end effector move
<img width="584" alt="m8" src="https://github.com/user-attachments/assets/267998ad-1b4f-49f9-95e9-bf8343ff835c">

and attached to this repository is the robot arm blender file 

