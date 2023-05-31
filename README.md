# EXP 03 - THIRD PERSON CHARACTER MESH:

###### NAME: AASHIMA NAZREEN SAYEED S
###### REG NO: 212221240002 

## AIM:

1. Import the animation assets: Obtain the animation files for jump, walk, and idle in a compatible format such as FBX or BVH. To import the animations, go to the Content Browser panel in Unreal Engine, right-click in the desired folder, and select Import 

2. Create a Separate folder and Import the Animations to avoid any chaos 

3. Create an animation blueprint: In Unreal Engine, animation blueprints are used to control character animations. To create a new animation blueprint, follow these steps: 
    a. Right-click in the folder where you imported the mesh and select Create > Animation > Animation Blueprint. 
    b. In the Animation Blueprint Editor, click on the Event Graph tab. 
    c. Drag the new character mesh from the Content Browser and drop it onto the graph. 
    d. Connect the Output Pose pin of the mesh node to the Final Animation Pose pin of the Final Animation Pose node. 
    e. Save the animation blueprint. 
    
4. Open the animation blueprint: Open the animation blueprint you created for your character in the Animation Blueprint Editor. 

5. Create animation slots: Animation slots help organize different animations and control their blending. To create animation slots, follow these steps: 
    a. In the AnimGraph tab of the Animation Blueprint Editor, right-click in the graph and select Add State Machine > Animation Layer. 
    b. Double-click the newly created animation layer to open it. 
    c. Right-click in the graph of the animation layer and select Add State Machine. d. Double-click the newly created state machine to open it. 
    e. Right-click in the graph of the state machine and select Add State. 
    f. Rename the state to "Jump" and repeat steps e and f to create states for "Walk" and "Idle".
    
6. Add animation assets to states: In each state, you will assign the corresponding animation assets. To add animation assets to the states, follow these steps: a. Double-click the "Jump" state to open it. b. Right-click in the graph and select Add 
State Result. c. Drag and drop the jump animation asset onto the graph. d. Connect the Result node to the jump animation asset. e. Repeat steps a to d for the "Walk" and "Idle" states, assigning the appropriate animation assets. 

7. Create required Variables for the state’s like “ISJUMP”, “SPEED”. 

8. Set up transition rules: Transition rules determine when the character transitions between different animations. To set up transition rules, follow these steps: 
    a. Double-click the "Jump" state to open it. 
    b. Right-click in the graph and select Add Transition Rule. 
    c. Drag the transition rule from the "Jump" state to the "Idle" state. 
    d. Repeat steps a to c for the "Walk" state, creating transitions from "Idle" to "Walk" and from "Walk" to "Idle". 
    e. Configure the transition rules based on your desired conditions. For example, you might want to trigger the transition from "Idle" to "Jump" when the character jumps, and from "Jump" to "Idle" when the jump animation is finished. 

9. Create a Anim Montage in Animation Folder To Manage the montages of the animations.

10. Connect the animation blueprint to the character blueprint: To connect the animation blueprint to the character blueprint and enable the animations in the game, follow these steps:
    a. Open the character blueprint associated with the third person character. 
    b. In the Viewport tab of the Blueprint Editor, select the mesh component of the character. 
    c. In the Details panel, under the Animation category, find the Animation Blueprint property. 
    d. Click on the dropdown menu and select the animation blueprint you created. 

11. Test the character: Compile and save all the changes in the blueprints and animations. Now, you can test the character's jump, walk, and idle animations by clicking the Play button in the Unreal Editor.

## OUTPUT:

### ANIMATIONS:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/b158a3fe-3240-4924-b60d-dad143bcba8e)

### STATE MACHINES:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/997a80d8-9734-4c90-a36d-02827a128d93)


### STATE DIAGRAM:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/7d929690-7c24-4345-9061-da992d185d7d)

### VARIABLES:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/28ef2db6-ac4a-498b-b286-394c520bedf8)

### IDLE TO WALK:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/c60a7474-83af-482c-ab80-8ae819b1551e)

### WALK TO IDLE:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/4f64f218-884e-48f1-b268-9d1a68f1eced)


### WALK TO JUMP:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/7aff0473-59d2-4599-8c38-fe597e0030b6)

### JUMP TO WALK:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/38e3050d-7c50-4cc2-961e-42db9b4ed19b)

### JUMP TO IDLE:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/b31ca365-aaa0-4152-bda0-2c03a48cb411)

### IDLE TO JUMP:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/f21e0e16-a9fb-42f3-bd18-179874b69798)

### ANIMATION BLUEPRINT:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/0e53f23d-3394-4a4e-8dbe-770b0c45f437)

### ANIM MONTAGE:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/7d66a112-8c48-48bd-b94d-3c3729beec80)

### THIRD PERSON BLUEPRINT:
![image](https://github.com/Aashima02/Third-Person-Character-Mesh-/assets/93427086/73c83090-5c42-4802-8b29-97d887f1b3b9)

## RESULT:

The third person character mesh has been successfully changed using animations.























