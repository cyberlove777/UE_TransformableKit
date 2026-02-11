# Transformable Kit is an Actor Component, spline based (Spline Component) tool to control transforms of any Actor.
This repository is plugin Documentation, Issues and Support Page

## Description
Kit consists of one customizable C++ class, derived from USplineComponent, Visualization Class to visualize actor's position and rotation at spline points and Details Panel Customization to set Actor's rotation at spline points.
Actual version is 2.0. Updated 02.2026.

![General Screenshot](/assets/images/readme/general.png)

## Links

[Documentation](https://github.com/cyberlove777/UE_TransformableKit/wiki)

[Fab Store Page](https://www.fab.com/listings/5add8893-aa29-4924-a472-dc106f2ee6de)

[Features](#features)

[Questions And Answers](#questions-and-answers)


## Features
1. Create a spline based traectory, for actor to go along it (Loops supported).
2. Setup Location And Rotation of your Actor at spline points. Rotations are linear interpolated between points.
3. Choose one of 5 modes to transform your actor (One Shot, One Shot Reverse, Loop Reset, Ping Pong, Parametric)
3. Set the Motion Duration (Transform duration) in seconds
4. The motion is linear by default, it is possible to set up Float Curve to create non-linear transform.
5. Use Action Points to bind your custom events as actor reaches some position at spline
6. Setup transform pauses, auto at loop\half loop end, or at any time in runtime with blueprints.
7. Set ignored component of Actor, that won't be transformed
8. Set Sweep\Physics teleport mode to interact with world
9. Set Initial transform to start from any custom point at spline

## Questions And Answers
