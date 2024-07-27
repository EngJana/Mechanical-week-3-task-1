# Mechanical-week-3-task-1

smart methods intership - mechanical discipline

# Robot arm Assembly and Control
This project involves the creation of robot legs using Blender for the 3D modeling using servo SG90 motors that move the legs. Each leg consists of three segments: hip, knee, and foot.

# Creating the Robot arm using Blender
## Generate the Robot arm shapes required:
- cylindricals for the bases and arm joints
- cubes for arm links 
Adjusting the shapes to create the arm: Using Blender tools and modifiers to adjust the links and joints measurements and prepare them for motor placement:
Move: for positioning and placing each link and joint to create the arm.
Rotate: Adjust the links and joints to the desired orientation.
Scale: Modify the lengths of the arm segments along each axis.
Bevel Modifier: Smooth the edges of the arm.
## Animation
1. Add Armature:
Go to Add > Armature 
2. Position Armature:
Switch to Edit Mode and adjust the bones to fit inside your character model. Ensure all major joints align correctly.
3. Parent Armature to Mesh:
Select the character mesh, then Shift + Select the armature.
Press Ctrl + P and choose With Automatic Weights to automatically assign weights based on proximity.
4. Adjust Weights:
Switch to Weight Paint mode to fine-tune the weights of the vertices for each bone, ensuring smooth and accurate deformations.
5. Add Animation:
With the armature selected, switch to Pose Mode.
Create keyframes by pressing I and selecting the type of transformation (e.g., Location, Rotation).
6. Animate:
Move the timeline slider and adjust the pose of the character. Insert keyframes at different points to create the desired animation sequence.
then press a then i.
7. Playback and Adjust:
Play back the animation using the timeline to check for any issues. Adjust keyframes and weight painting as necessary to improve the animation.
