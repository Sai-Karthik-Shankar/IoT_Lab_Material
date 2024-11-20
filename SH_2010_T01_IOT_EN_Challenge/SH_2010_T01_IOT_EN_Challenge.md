<!--- Learning Lab "Digital Technologies"
Author: Holger Günzel 			Date: 2020 May 04  Changes by: Holger Günzel - 2020 Oct 03 - logo
Sonja Hofauer  - 2020 Sept 02 - adapted for FHWS
Sai Karthik Shankar - 2024 Nov 10 - adapted for raspberry pi 5 support
--->

**Learning Lab: Internet of Things (IOT)**  <img style="float:right" src="../8000_Global_Files/THWS.png" height="50">  
2024/25 winter semester | module |  

***
# Assignment 9: The IOT Challenge 

<!-- Vorsichtiger Umgang, Runterfahren, vom Strom nehmen
DOKUMENTATION -->
## Objectives
- Executing your own project
- Remember your learnings

## Required Equipment
- Installed and running Raspberry Pi with OS
- Connection to the Internet
- Power supply for the Pi 
- Monitor with HDMI cable
- Keyboard and Mouse connected via USB  
- SenseHat
- Additional material (like LEDs, etc)
- NodeRED

## Challenge Description
Let us consider the following situation. Schweinfurt wants to take the next step towards a "Green City" with IoT and the focus on traffic. You are responsible to develop a first prototype using NodeRED, SenseHAT and a Raspberry Pi. For the first prototype no integrated solution has to be developed. 

Here are the main aspects of "Green City Schweinfurt":

- Project vision: We want to carry out a project that will **revolutionize the traffic.** Our Vision: **"Sustainability and safety first with IoT"**.  The roads have to be managed by means of central control of the process and parameters for more sustainability for the environment and safety for all participants in traffic.
- We distinguish the following roles: **administration, drivers and pedestrian** (ok, very limited focus ...)
- Our **User Stories** (i.e. the requirements) - Before you start, prioritize the requirements according to business value. What should be done first, as it is most important?
  - The driver can change to level 3 automation (two presses on the joystick). The LEDs of the SenseHAT show blue color.
  - The administration need a central display of the environmental temperature in the town hall to make the right decisions.
  - The pedestrians want to change the pedestrian traffic light from red to green with their smartphone (hint: try to access the NodeRED dashboard from your smartphone).
  - eCall system: when the IMU detects a shake (threshold >1), an MQTT message is send out and the warning lights are turned on (LED matrix flashes red)
  - In case of a detected traffic jam(ML model), administration and nearby drivers are informed (MQTT message)

<!--
  - Optional: The drivers follow the traffic lights in the car (on the Sensehat). Visually, 3 LEDs of the row are to be switched in the right order and color. After a random time (max 3 sec) all LEDs go out. -->

## Further Inputs

## Hints


## Useful Resources for Own Searches
Node-RED and Sensehat


## Retrospective
Please answer the following question(s) 

1. What happened during the project?
2. What have you learned?

and document each answer.

## Source(s)
- Lars Brehm, Holger Günzel: "Learning Lab: Home Automation with Internet of Things (HAT)" https://www.ll4dt.org/