# Storage Management Robot

## Overview

This project presents a conceptual design for an automated storage management system. The robot is designed to retrieve items from tilted shelves and deliver them to a basket using a conveyor mechanism.

## Components

The system consists of three main parts:

1. **Tilted Shelf Unit**  
   A large frame containing multiple shelves that are slightly tilted forward. This tilt allows items to naturally slide toward the front when one is removed, making it easier for the robot to access them.

2. **Robotic Picker**  
   Positioned between the shelf unit and the conveyor belt, the robot features a simple gripping mechanism. It can move vertically and horizontally to reach and retrieve items from various shelf levels.

3. **Tilted Conveyor Belt**  
   Located on the opposite side of the robot, the conveyor belt is slightly inclined. Once an item is placed on it, gravity causes the item to slide down into a collection basket at the bottom end.

## Steps

1. The robot scans shelf tags to identify the location of the requested item.
  
2. It navigates to the correct shelf position and picks up the item using its gripper.
  
3. The robot then rotates and places the item onto the tilted conveyor belt.
  
4. The item slides down the conveyor and falls into a basket for easy collection.

## Working Envelope
The working envelope defines the robot’s reach and movement area needed, it includes:

1. Pick items from any level of the tilted shelf
  
2. Rotate to the convyor belt side.
  
4. Place items on the conveyor belt.
