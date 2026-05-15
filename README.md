# InterfaceRobotExplorateur - First-Year SRI Project 2023/2024

[Français](README.fr.md) | English

![Angular](https://img.shields.io/badge/built%20with-Angular-red)
![Status](https://img.shields.io/badge/status-completed-green)

Angular interface for controlling an autonomous explorer robot as part of the first-year SRI project at UPSSITECH Toulouse.

The robot can:

- map its environment,
- understand voice commands,
- follow colored balls,
- be controlled manually from the interface.

## Main features

- Mapping mode: real-time display of points detected by the Lidar.
- Voice command mode: audio recording, sent to the Flask backend, interpreted, then converted into a command sent to the robot.
- Manual control mode: direction buttons with live video feedback.
- Ball tracking mode: visual detection with dynamic selection of the color to follow.

## Technical stack

- Frontend: Angular v17.3.3
- Backend ([repository](https://github.com/MaelaViguier/mobile_robot_backend)): Flask, Python
- Robot: Raspberry Pi and Arduino

## What I learned

- Angular development: modules, components, routing.
- Communication with a Flask backend using HTTP/REST.
- Integration of sensor feedback: camera and Lidar.

## Status

Project completed in 2024. It was used during demonstrations to validate the cross-disciplinary skills developed during the project.

This project was also used as a development platform during [HackaTAL 2024](https://hackatal.github.io/2024/), a hackathon focused on Natural Language Processing and generative AI applied to converting audio into robot commands.

## Run the project locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Bebel19/interface_robot_explorateur.git
   cd interface_robot_explorateur
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   ng serve
   ```
   
## Démo
<div align="center"> <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/image/20240512_195038.jpg?raw=true" alt="Robot explorateur" width="400"/> <br/> <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/video/robot_explorateur.gif?raw=true" alt="GIF du robot explorateur" width="800"/> </div>


University project — UPSSITECH Toulouse
