# POLYMORPHISM-Traffic-Management-System

## Description

This project demonstrates the concept of Polymorphism in Python using a Smart Traffic Management System.

A parent class named TrafficDevice defines a common method called activate(). Several child classes inherit from it and provide their own implementation of the method.

The child classes are:
- TrafficLight
- SpeedCamera
- PedestrianSignal
- EmergencySiren

Each object is stored in a list and activated using the same loop. This shows how different objects can respond differently to the same method call without checking their types.

## Concepts Used

- Classes and Objects
- Inheritance
- Method Overriding
- Polymorphism

## How to Run

1. Open the project in PyCharm.
2. Run the Python file.
3. The program will activate each traffic device and display its unique action.

## Output
Activating Smart Traffic Devices...

Traffic Light: Green light is now ON.
Speed Camera: Monitoring vehicle speed.
Pedestrian Signal: Walk sign displayed.
Emergency Siren: Emergency vehicle approaching.

## Author

Joel Marfo
