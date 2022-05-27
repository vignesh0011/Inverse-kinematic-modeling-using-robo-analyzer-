# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values of X and Y wherever necessary.
4. simulate the model for inverse kinematics.
5. plot the graph between the joints.
6. update the DH parameters of the link configuration and end effector configuration.







### SIMULATION 

### 2R PLANAR
![1 1](https://user-images.githubusercontent.com/75235212/170625826-0b1e2cb2-2514-4d5c-96a1-be15bd75d8c9.png)

 
 
 
 ![1 3](https://user-images.githubusercontent.com/75235212/170625870-9e75a3f8-f7f1-4bbd-a6c9-ff551ad221bf.png)


### 3R Articulated
![2 1](https://user-images.githubusercontent.com/75235212/170626055-b6127362-2386-4295-9841-05adc16e245f.png)


![2 3](https://user-images.githubusercontent.com/75235212/170626074-3cecd9a8-1cb1-4f6f-9362-a8932d3edc8d.png)

 
 
 ### PLOT 
 
 ### 2R PLANAR
 
 ![1 2](https://user-images.githubusercontent.com/75235212/170626125-40bcad83-39f3-466e-a61e-4dd461c20578.png)


![1 4](https://user-images.githubusercontent.com/75235212/170626146-e9967343-194d-42e5-af81-d13d3ffd5f98.png)

### 3R Articulated

![2 2](https://user-images.githubusercontent.com/75235212/170626411-1b1c76dc-5632-4cf7-a691-74f8c50f6ad0.png)

 
 ![2 4](https://user-images.githubusercontent.com/75235212/170626426-53758a45-3bcd-41b1-8845-917922f4d69d.png)


### RESULTS :

Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given  input end effector position is plotted.
