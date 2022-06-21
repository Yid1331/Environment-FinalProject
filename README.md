# Environment-FinalProject:Horror Environment Adventure (Under continuous development...)

### 00 Overview

Three years ago, the director of a small private hospital was killed. The suspects were identified as four people: the director's wife, the hospital cleaner, the owner of the hospital coffee shop, and a patient. The case was abruptly terminated during the investigation and the hospital was abandoned, but the scene remained as it was on the day of the crime. Much evidence and clues were kept at the scene.

The players, as an intruder, accidentally broke into the hospital. Everything around them can interact with players in unexpected ways. What all the player has to do is to observe and use the surrounding items, explore the previous story of this abandoned hospital. If players are accidentally locked somewhere, they may try their best to escape there. Reminder: DON'T BE DISCOVERED BY ANYONE.

### 01 Developer Readme

This project was completed by myself. My goal is to master the basic operation of Unreal Engine through this project, and continue to improve this game work after the course. In this work, I want to let players experience the immersive horror atmosphere in the following ways:

1. Horror and realistic game environment
2. Interaction methods that mobilize the player's senses (visual, auditory, and action)
3. Unexpected plot settings

#### Horror and realistic game environment

Because I set a certain story background for this game, that is, there are 4 suspects, so first I designed the room layout of this hospital, including the hospital front desk, the dean's office, the canteen, the coffee shop, the infirmary, the ward, Operating room, toilet, a total of two floors. The initial scene setup is as follows:

![Screenshot_1](https://user-images.githubusercontent.com/81423727/174865407-019a67cc-8bcd-4c0d-a442-547dae5efcc3.png)

[Initial Layout Video Link](https://www.youtube.com/watch?v=_aKa5pxfTho)

After completing the initial layout design, I used the assets and the items I modeled to refine the game environment, making the environment a very realistic effect.

![1](https://user-images.githubusercontent.com/81423727/174867460-e9c92767-3543-4085-8cd7-2b4b2b318d52.jpg)

[Final environment Video Link](https://www.youtube.com/watch?v=2ZkwiT8vbDg)

#### Interaction methods that mobilize the player's senses (visual, auditory, and action)

**Changeable movement speed**

First, I imagined the action of the character in this horrible environment. I think that people rarely jump in a scary indoor environment, but gradually increase their pace in emergency situations, so I set the mouse wheel as the character's movement speed's controller, in an emergency, the player can speed up the movement of the character by sliding the scroll wheel. Blueprint as follow:

![Screenshot_9](https://user-images.githubusercontent.com/81423727/174869293-5cf9f8be-a065-4265-89ea-2aed68061689.png)

**Squat down and watch carefully**

In addition, I also set the squatting action for the character, because there are many objects in the environment that need to be observed closely, and squatting to see is very consistent with human instinct. The blueprint is as follows:

![2](https://user-images.githubusercontent.com/81423727/174870309-9081b841-e659-4c05-af93-c7754e453928.jpg)

**3rd person to first person**

In order to make the player more immersive, I prefer the first-person perspective characters, but I prefer the player to look down (the camera is turned to the bottom) to see their own body, so I converted the third-person camera to the first-person and repaired the problems with camera penetration inside the character model.

![Screenshot_12](https://user-images.githubusercontent.com/81423727/174871470-7c6bb7a4-c3c7-4c60-a754-c3fdac176e1e.png)

**Sound effect**
I bound the camera to the head of the character's skeleton, and equipped the character with breathing sounds and footsteps on the ground with different textures, all to give players a more realistic experience.



