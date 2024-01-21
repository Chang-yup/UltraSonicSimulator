# For Users
## How to use
### Set Configuration
1. Reference for Ultrasound sensor
2. Configuration for Reflection
3. Create Objects and Configuration (car, object, sensor, ...)

### Run Simulation

### Get your Result

# For developers
## License

## Directory Tree
./core : C++ code for USS Simulator Core Code + User Code
./core/engine : USS Simulator Engine
./core/application : USS Simulator Application
./public : USS Simulator GUI / Controller

## Ultrasound Mechanism
Reference: https://blog.naver.com/iotsensor/221167562053

(Distribution Picture will be inserted)
distribution : Ultrasound can be distributed in transimission medium (like air). and It is spherical wave.

(Absorption Picture will be inserted)
Absorption : Ultrasound can be reduced in amplitude when passing through the transimission medium or hitting the sound-absorbing material.

(Reflection Picture will be inserted)
Reflection : Ultrasound can be reflected when hitting another material. the reflected wave can be various forms of wave.

(In this simulation, Diffraction and Refraction is not considered)

## Architecture
(Architecture Picture will be inserted)
MVVM Pattern is used for this project. 

User can interact with GUI(HTML/CSS/Javascript) then initialization data is transmitted to Core(C++).
If every calculation(simulation) is done, result will be updated on GUI.

Developers can add their application in './core/application'. 

## GUI
https://www.figma.com/file/I6OEdddZGfWmW41yYO2ETW/Ultrasonic-Sensor-Simulator?type=design&node-id=0%3A1&mode=design&t=p7JIrMLv6NiqWr52-1
wireframe for this project.

## Core - Engine

## Core - Application
Developers can add their application in './core/application'. 
This project is focused on automotive application developers. You can adapt this on your research project.

### How to check Application result
