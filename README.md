# Ultrasonic-Challenge

## Description Hello

A semi-realistic Dodge Challenger SRT  Demon with an ultrasonic sensor that picks up objects in its path and turns to the right in order to avoid collision.

## Picture

![Shell of Car](https://lh6.googleusercontent.com/CkJlYhsXQAjbptlFUzJ50KT8anF-K2JSYp-2tQ9huOfhPNiQLyK-rWR6ar6Yb3Al5NS5c6PaDaQunu7UCmQp0g4k_tEnLgoBX30lx4iHeRVAONL4bpSpO4dN7Oa3BBK-Zp9b4MH9)

## Goal 

Our Goal is to create a realistic car in Solidworks.

## Possible Solutions 

### CAD 
1) Full 3D printed shell of a car with the sides being detachable
2) Midsection of car being 3D printed, and attaching laser-cut acrylic walls to the sides

* We picked the second option. Printing the full 3D body of the car would be extremely expensive, requiring the printer to put down a large platform of material before it even started building the actual car. The second option was much more economical, with the detachable walls allowing you to pull out any of the inside components in order to fix any problems that arise.

### Code 

1) So you don't have to calculate how far you need to start turning you could have it move very slowly
2) Instead, if it is even closer you could possibly move one of the servo’s slower and the other faster for a sharper turn 

* We chose the second option so it is more realistic to a car.  

## Schedule

### Code

* December 6th - Finish Planning 
* December 13th - How fast the Servo's should move
* December 13th - How far away it needs to start turning
* December 18th - Fritzing Diagram Completed

### CAD 

* December 2 - Finish basic shell of the car with components on the inside 
* December 3 - Finish holes for assembling the walls to the car body 
* December 6 - Finish final virtual assembly including everything
* December 10 - Start Printing the car body
* December 10 -Laser Cut the walls

## Parts

### Solidworks

* Creation of the Shell
* Creation of the Walls
* Assembly or the Car
* Drawing for the Walls

### Arduino 

* Code for Ultrasonic Sensors 
* Code for Servos moving forward
* Code for Servos turning right 
* Code for Servos making a sharper turn

### Wiring 

* Four Continuous Servos 
* One Ultrasonic Sensor
* One Arduino Uno
* Jumper Cables

### Materials

#### Code

* 6AA Battery holder
* Arduino Uno
* Mini Breadboard
* Prototyping Shield
* HCSR-04 Ultrasonic Sensor
* AWG22 Wire

#### CAD

* 3D Printed Shell 
* Laser Cut Acrylic Walls
* Nuts and Bolts

### Attachments 

* PsuedoCode https://docs.google.com/document/d/1yPundpz824h06et9DYhnXZwOlaTkPOGDrPb8JvVqRH0/edit

*********************

## Changes During Project

* We pretty quickly realized the schedule we made was unrealistic, and soon we were way off track compared to our original schedule


### CAD 
*Had to create chamfers on one side in order to cut down the amount of 3d plastic structure
*Etched the original reference blueprint into both transparent acrylic walls
*Added a hood scoop to the front of the body
*At first I forgot to add holes to secure the servos to the walls

### Code

During the project a few changes had to occur……. 

#### Flat Wiring 

There wasn’t enough clearance at the top of the car so we had to flat wire our arduino.  We had to rewire 4 times, through processes of trial and error to get everything to fit. 

##### Lessons Learned

* Make room for wiring to save so much pain 
* If you don't want to have clearance then decide that before the project so you flatwire the first time.


#### Using a Mean

Our ultrasonic sensor had some trouble with oddball readings so I added in some code for a mean. I had it add up the last 5 readings and divide it by 5 and then use that number for the actions in the code.

# Post Project 

### CAD 

*Think through what holes are needed and make sure you have a plan to secure all parts before you start

### Code

One thing after we finished the project is that we need to have more realistic goals for our project.  We have to factor in time for things to go wrong, as well as give more time so we can realistically get it done.  

![Code Part One](https://raw.githubusercontent.com/dstuken31/Ultrisonic-Challenge/master/Code_Picture_Part_One.PNG)

![Code Part Two](https://raw.githubusercontent.com/dstuken31/Ultrisonic-Challenge/master/Code_Picture_Part_Two.PNG)

### Overall Lessons Learned 

* Plan realistically but effectively 
* Communicate with your partner 
