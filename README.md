# EX.NO:2 Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.open the roboanalyzer software.

2.select the robot and its degrees of freedom.

3.change the values with the link lenght wherever necessary.

4.simulate the model for forward kinematics.

5.plot the graph between the link and the joints.

6.update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 
 
 ![199652215-9f09686d-f26d-4311-a244-063763bea834](https://user-images.githubusercontent.com/88670187/205494790-ab4301c5-cbe1-4c15-8e94-e8aa3f0281dd.png)
![199653810-722e82e3-d0f6-430c-ad57-5b94a3451eae](https://user-images.githubusercontent.com/88670187/205494794-ef6095ee-9f10-4fda-b38b-7d6c1617319f.png)
 
 ### PLOT 
 ![199652288-2cb387dd-449f-4eed-a8ae-b1f4371478b6](https://user-images.githubusercontent.com/88670187/205494805-a0234ae7-9bfa-4d85-8533-78d37241765d.png)
 ![199653876-21e89d69-8655-4439-ade0-bdcfc8c54b1d](https://user-images.githubusercontent.com/88670187/205494817-51ded231-b318-4bf0-afb0-9be6a1cae1a0.png)


### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
