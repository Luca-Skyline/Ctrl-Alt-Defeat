# Ctrl+Alt+DEFEAT
Robotics Team:
- Luca DalCanto (**Builder**, Programmer)
- Kai Rosenbluth (**Programmer**, Documenter)
- Jacob Scher (**Driver**, Builder)
  
Skyline High School 2023-2024. <br>
Format: (**Official Role**, Additional Role)
# 

## Objective:
An offensive, fast, manueverable robot, possibly equipped for competition in the V5 competition Over Under.

## Planned Capabilites:
- Omnidirectional drive 
- Rotate while driving in one direction (with two drivers)
- Intake and throwing capability of a Triball



# Chassis Design 
## X Drive
### X-Drive. A four wheel bot with each wheel in the corner of a square frame and the sides of each wheel facing central. 
# 

This is the most manuvurable of the chassis and can change directions without turning. The four omnidirection wheels are able to mantain a motion on any combanation of the four axis while being able to manuver the arm in a manner to be able to manipulate the Triball. It is also quite fast compared to all of the options as it does not need to slow down to turn and can pivot in place. We think using this omni-directional chassis will not only improve the programming of the bot, not requiring as many steps to turn, but also help the human driver manuver the bot in a quick and timly manner. On top of that, it is the most unique looking chassis so we have a further incentive to pick it as it will make our bot stand out in the padock and show the judges that we are able to come up with new and more unconventional drivetrains instead of following the norm. It is also possible that the bot can be controlled by two operators, a driver and an arm manipulator. Because the bot can pivot while driving and maintain the same direction, the driver can focus on posistioning the bot and the AM can focus on grabbing Triballs.

<br />
<br />

## Brainstorming 

### Topdown Sketch (Initial Design)
![Top view of first bot concept](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/topdown.JPG)

### Sideview Sketch (Initial Design)

![sideview](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/550bcf93-66c5-4dce-9857-a8a38713aa8c)

<br />
<br />

## Chassis Models  

### Chassis Digital Diagrams (Model #1)
<img src='https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/6ec0d30d-715e-4fe1-871f-65528199240c' width='500' height='500'> <img src= 'https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/f896e13b-1e28-488b-9480-bc3b1e7fd162' width='500' height='500'>


This was our initial design after looking at some references online and thinking through its viability. After some consideration looking at our robot pieces, we decided to change our robot's chassis design is order to better protect the wheels and provide better placement for the brain. 

### Chassis Design Digital Model (Model #2)
![chassis model 2](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/7aa6b86f-d730-454d-8535-857c584bf327) 

This is own new chassis design with the two main bars being closer inwars creating a more rectandular shape. 

### Measurements Chassis Digital Model (Model #2)

<img src='https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/87e8406b-73c4-43c5-b939-80b0255f957a' width='500' height='500'> <img src= 'https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/119f9b45-6d46-4d40-989b-26a7f9db8b8b' width='500' height='500'>

These models show the measurements of our chassis which is almost exactly 35 by 35 holes with a hole translating to "". So around "" by "". 


### Updated Chassis Design Digital Model (Model #2)
![chassis 2 updated model](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/119f9b45-6d46-4d40-989b-26a7f9db8b8b)

This is the most accurate model of our chassis with more improved wheels and hole measurements included. 

### Chassis Digital Model (Model #2) (Sideview) 
![chasis 2 sideview](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/6c6a54d4-e229-4887-a1ef-cc4bbd1f578b)


## Chassis  Model (Sideview and Topview) 

This is our real life chassis after finishing most of the building. 
![images/side_chassis.JPG](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/fa414729e3f74d0d5329e4f7f616793d5b98eec3/images/side_chassis.JPG)
![top chassis](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/fa414729e3f74d0d5329e4f7f616793d5b98eec3/images/top_chassis.JPG)

<br />
<br />
<br />
<br />
<br />

# Intake Design 

## Brainstorm 

### Throwing Arm Design (Sketch) 
![single arm concept](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/IMG_2786.JPG)
If given near-180 degree rotation vertically, this arm could also trow triballs with high accuracy. When on defense, it could sit touching the ball load zone, get constantly loaded with triballs, and throw them constantly into our zone. We'd need to design a way to make it fast and strong, possibly with a rubber band system (just have to make sure our robot doesn't beat itself up too bad with repeated stopping of this high velocity arm!!)

How to throw something (Jacob):
- Rubber band snaps arm back (Only 90 degrees of rotation)
- Motor throws (Too little power)

### Intake Diagrams (Idea #1) 
<img src='https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/e11db840-8a0c-4e0a-9806-d87dace37599' width='400' height='500'> <img src= 'https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/2c4c3f61-0294-4844-b334-4e48eba99ce0' width='600' height='500'>

We brainstormed some ideas around how the robot would collect and move the triballs around. Our first idea revolved around these gree wheels being moved to make contact with triballs and then rotating to bring thm in and let the robot hold them. This would double as a possible distrobution system with the wheels rotating the opposite direction to throw the triballs int he desired direction. Moreover, the design also contains a piston (as seen with the red dot in the left diagram) to hit the balls in the desired direction. The piston can provide power and distence the wheels might not be able to. 

## Implemented Arm Design 

We decided on initially remove the wheels due to a lack of materials and a lack of effectiveness in testing. Instead we focused on a push system for the bot, deciding on adding wheels and better intake later. We have a metal bar that can be pushed in and out with a button to assit in moving triballs. 

### Arm Sideview (1 and 2) 
![arm sideview 1](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/37347d8f-33a2-46d4-b1cb-b8ca8cf6d7de)

![arm sideview 2](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/e718d2d3-c25d-401b-81d6-aa2fc82b0943)

### Arm Topview 
![arm topview](https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/FinalPushSystemTopview.png?raw=true)

<br />
<br />
<br />
<br />
<br />


# Programming Design

For the programming we wanted to set it so one controller controled the vertical and horizontal movement of the bot while another control determined the bots rotation and intake system. 

## Planning After Drivetrain: (outdated)

<img src='https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/IMG_2861.JPG' width='500' height='400'> <img src= 'https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/IMG_2863.JPG' width='500' height='400'>

<img src='https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/blob/main/images/IMG_2889.JPG' width='500' height='400'> <img src= 'https://github.com/Luca-Skyline/Ctrl-Alt-Defeat/assets/89172997/b918bb2d-08e8-441c-8901-40a07512c15d' width='500' height='400'>






### Current Progress Images:


  
# Game Progress  

Our class decided to have our robots face off against each other in various games. We focused on the robot soccer and robot sumo activities. 

## Sumo 
Our robots design was not ideal for sumo do to the spread out wheels and light frame of the robot causing it to not put up much resitence when directly pushed against. 
Regardless we still competed against classmates in casual competition and did quite well. 

## Soccer  
Our robot was well designed for soccer due to its omni directional capibilities and speed. We also implimented a arm design so we could hit the triball.  

