# Mechanical Week 3 Task 1

Smart Methods Internship - Mechanical Discipline

## Robot Arm Assembly and Control

This project involves the creation of robot arm using Blender for 3D modeling

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

robot movement 
<img width="582" alt="m3" src="https://github.com/user-attachments/assets/ad01567e-1ac0-4ca4-a314-3ab5b31bac41">
<img width="578" alt="m4" src="https://github.com/user-attachments/assets/ebf2deed-51a6-4c7b-a829-f58e459b5c6f">
<img width="581" alt="m5" src="https://github.com/user-attachments/assets/7b32dd90-5bd8-4cb7-9968-899f5685074e">
<img width="583" alt="m6" src="https://github.com/user-attachments/assets/b6aa261e-30e5-4844-9f36-52fcda125d5e">
<img width="581" alt="m7" src="https://github.com/user-attachments/assets/4af3661a-6333-4b9f-a0f1-6805e60b331b">
<img width="584" alt="m8" src="https://github.com/user-attachments/assets/267998ad-1b4f-49f9-95e9-bf8343ff835c">

and attached to this repositry is the file 

