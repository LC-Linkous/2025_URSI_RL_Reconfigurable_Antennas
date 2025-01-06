# 2025_URSI_ML

# NOTE: Code and full tutorials will be released after pubication

Repository for code and demo featured in "Reinforcement Learning Controlled Mechanically Reconfigurable Antennas" presented at the 2025 United States National Committee of URSI National Radio Science Meeting (USNC-URSI NRSM), Boulder, CO, USA. 


## Table of contents
* [Overview](#overview)
* [Requirements](#requirements)
* [How to Use](#how-to-use)
* [Tutorials](#tutorials)
    * [Tutorial 1: Running the Simulation](#tutorial-1)
    * [Tutorial 2: Patch Antenna Calculations and Fabrication Made Simple](#tutorial-2)
    * [Tutorial 3: Reading from the TinySA Ultra](#tutorial-3)
    * [Tutorial 4: Communicating with the Heltec LoRa V3](#tutorial-4)
    * [Tutorial 5: Creating and Assembling the Rail System](#tutorial-5)
    * [Tutorial 6: Testing the Servo Motors](#tutorial-6)
    * [Tutorial 7: Wiring it All Up](#tutorial-7)
    * [Tutorial 8: Mechanically Reconfigurable Antennas](#tutorial-8)
    * [Tutorial 9: Writing Your Own RL Algorithm](#tutorial-9)
* [Resources](#resources)
* [How to Cite](#how-to-cite)




## Overview
This repository features code for the following:
* A Python-based simulation for mechanically reconfigurable antennas  
* Arduino code for a Heltec LoRa V3 reciver that controls 3 servo motors for linear, pan, and tilt movement
* Arduino code for a Heltec LoRa V3 transmitter that sends servo commands to the receiver



Supplemental code is featured on the following repos:
* [TinySA Ultra Python library]()



Tutorials for the mechanical build are featured on the [wiki]() attatched to this repo. Links to specific aspects are included below in [Tutorials](#tutorials)



## Requirements
A full list of final hardware and software requirements will be relased post conference

### Software Requirements


### Hardware Requirements



## How to Use




## Tutorials

These tutorials detail the full design and construction process for this project. They are written to be accessable for everyone from a beginning student to a professional


#### Tutorial 1: Running the Simulation

[WIKI LINK]

<br>

The code in the ./RL_Simulator directory has two options for running:
1) **Simulation Only** - The option for 'no hardware' can be selected to run this Python code in 'simulation only' mode. In this mode, RL algorithms can be tested without the need for hardware. This mode is meant for exploring and fine-tuning new algorithms without the worry of working with hardware or other equipment. The GUI shows several directional radiation patterns and representations of TX power as visual appoximations for the cost functions. 
2) **Simulation with Hardware-in-the-Loop** - The second option for running the simulation with hardware-in-the-loop is for real-world testing of implemented algoritms. The UI tracks some position approximation, but the RL algorithm uses collected data and known servo positions.

<br>

**Simulation ONLY**

<br>


**Simulation with Hardware in the Loop**



#### Tutorial 2: Patch Antenna Calculations and Fabrication Made Simple
This tutorial covers creating the 1.5 GHz patch antennas used for the mechanical reconfiguration


#### Tutorial 3: Reading from the TinySA Ultra
This tutorial walks through the [TinySA Ultra API](), the data collection, and how to test the hardware. Several alternatives are suggested, though their support in the project is not included.

#### Tutorial 4: Communicating with the Heltec LoRa V3
Using the Arduino IDE to program and communicate between two LoRa units

#### Tutorial 5: Creating and Assembling the Rail System
Includes:
* Full physical parts list for the rail system + some alternatives
* The CAD files for 3D printing the mounts
* General soldering + wiring instructions
* Testing instructions
* General troubleshooting

#### Tutorial 6: Testing the Servo Motors
Includes:
* Arduino code for testing the 3 types of servo motors
* Instructions for zeroing out the servos
* Testing instructions
* General troubleshooting


#### Tutorial 7: Wiring it All Up
Wiring diagrams, step-by-step instructions, and how to work with power safely. 


#### Tutorial 8: Mechanically Reconfigurable Antennas
Testing and operating the fully assembled system

#### Tutorial 9: Writing Your Own RL Algorithm
How to include your own RL (or other) algorithms in the program


## Resources




## How to Cite

PENDING

