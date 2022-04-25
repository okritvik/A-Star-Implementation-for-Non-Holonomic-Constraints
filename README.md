# A-Star Path Planning - Turtlebot3 (2D Map)
Project - 03 (Phase 02, Part-01) for the course, 'ENPM661 - Planning for Autonomous Robots' at the University of Maryland, College Park.

Implementation of the A-star algorithm for path planning of the Turtlebot3 robot with a Non-Holonomic action set in a 2D Map. 

## Team Members:
* Kumara Ritvik Oruganti (117368963)
* Adarsh Malapaka (118119625)

## Required Libraries: 
* cv2 : To add lines or circles in the map at the desired coordinates.
* time: To calculate the running time for the Dijkstra algorithm.
* numpy: To define the obstacle map matrix
* heapq: Heap Queue to store opened_list nodes 

## Test Case 1: 
  [co-ordinates with respect to bottom left corner origin of the window] 

	Start-Node: (15, 15)

	Goal-Node:  (350, 150)
  
  Robot Clearance: 10
  
  RPM1: 1
  RPM2: 2
  
  Initial Heading Angle: 0

<p align="center">
  <img src="https://user-images.githubusercontent.com/40534801/165003066-51e241eb-f271-428b-a3a9-5ddc13a78886.png" width="800" height="500">
</p>


## Test Case 2: 
  [co-ordinates with respect to bottom left corner origin of the window] 

  Start-Node: (300, 30) 

	Goal-Node:  (150, 150)
    
  Robot Clearance: 10
  
  RPM1: 1
  RPM2: 5
  
  Initial Heading Angle: 90

<p align="center">
  <img src="https://user-images.githubusercontent.com/40534801/165003074-a181345c-e553-4b4d-acde-52d0182c176f.png" width="800" height="500">
</p>

## Running the Code:

The code accepts the start and goal positions from the user through the command-line interface as mentioned below.

**Format/Syntax:** 
		`python3 a-star.py`

**For Test Case 1:**	
		
     ```
     python3 a-star.py
     Enter the robot's clearance: 10
     Enter Left Wheel Velocity in RPM: 1
     Enter Right Wheel Velocity in RPM: 2
     Enter the X Coordinate of the Start Node: 15
     Enter the Y Coordinate of the Start Node: 15
     Enter the X Coordinate of the Goal Node: 350
     Enter the Y Coordinate of the Goal Node: 150
     Enter the Initial Head Angle: 0 
     ```

**For Test Case 2:**	
		
     ```
     python3 a-star.py
     Enter the robot's clearance: 10
     Enter Left Wheel Velocity in RPM: 1
     Enter Right Wheel Velocity in RPM: 5
     Enter the X Coordinate of the Start Node: 300
     Enter the Y Coordinate of the Start Node: 30
     Enter the X Coordinate of the Goal Node: 150
     Enter the Y Coordinate of the Goal Node: 150
     Enter the Initial Head Angle: 90
     ```
