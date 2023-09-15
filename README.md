I've got a couple of projects mostly for learning purposes, but you might want to check out these ones:

## [TwitchMicroscope](https://github.com/mateuszbugaj/TwitchMicroscope)
It is a (Java) chatbot that allows the control of a [Cartesian Manipulator](https://github.com/mateuszbugaj/CartesianManipulator) (with a real microscope) securely and easily using user-defined commands. <br/>
I have also implemented firmware (C lang) that controls this Cartesian Manipulator and a controller for stepper motors used in this Manipulator. <br/>
So the stack looks like this: <br/>
[TwitchMicroscope](https://github.com/mateuszbugaj/TwitchMicroscope) >> [CartesianManipulator](https://github.com/mateuszbugaj/CartesianManipulator) >> [A4988Controller](https://github.com/mateuszbugaj/A4988Controller) >> [HALibrary](https://github.com/mateuszbugaj/HALibrary) <br/>

## [GenericI2C](https://github.com/mateuszbugaj/GenericI2C)
This is a bit banged implementation of the I2C protocol developed and tested on the AVR microcontroller. <br/>
[GenericI2CDemo](https://github.com/mateuszbugaj/GenericI2CDemo) is another repository in which I use this library to communicate with a gyroscope, read values from the digital encoder, and connect two AVR microcontrollers as transmitter and receiver. <br/>
For fun, I made this simple but useful [logic analyzer](https://github.com/mateuszbugaj/SimpleLogicAnalyzer) using Arduino to read signals and JavaFX as a desktop application to show them. <br/>

## Neural network stuff
### [Position and rotation CNN](https://github.com/mateuszbugaj/Position_and_rotation_CNN)
This is my system based on convolutional neural networks that learn how to estimate the relative position and rotation of 3D models from generated images.
### [Inverse Kinematics with AI](https://github.com/mateuszbugaj/Inverse-Kinematics-with-AI)
This genetic algorithm learns to control the 2-segment arm to perform basic inverse kinematics and reach the target.
### [Neural Network-based pathfinder](https://github.com/mateuszbugaj/Neural-Network-based-pathfinder)
This genetic algorithm learns to reach the target and tries to follow a road as much as possible.

## Other
### [WaveFunctionCollapse](https://github.com/mateuszbugaj/WaveFunctionCollapse)
Implementation of the wave function collapse algorithm in Python to generate infinite patterns based on examples.
