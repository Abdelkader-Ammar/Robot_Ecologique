# Robot Delivery Interface

## Description
This project is a Java Swing application that simulates a robot delivery system. The interface includes visual components like a map and solar recharge stations. Robots can move on the map, connect to the system, and recharge automatically when entering a solar station zone. The system also manages robot behavior, connections, and exceptions.

## Authors
- Adem Kefi
- Abdelkader Ammar

## Project Structure
The project includes the following files:

- **app.java**: Entry point of the application (contains the `main` method)
- **Connectable.java**: Interface defining the structure for connectable robots
- **RobotLivraisonInterface.java**: GUI and main logic of the delivery interface
- **SolarStation.java**: Defines behavior and display of solar recharge stations
- **robot.java**: Base class representing a robot and its core functionalities
- **robotConnecte.java**: Subclass for connected robots with extended behavior
- **robotException.java**: Custom exception class for robot-specific errors
- **robotLivraison.java**: Subclass for delivery robots with specific delivery logic
- **robot.png**: Image resource representing the robot icon in the interface

## Prerequisites
- Java 21 or higher
- Java Swing (included in the JDK)

## Features
- Visual interface to track and control robot delivery
- Mouse interaction to update robot coordinates
- Automatic recharging when a robot enters a solar station
- Modular and extensible object-oriented design
- Custom exception handling for robot behaviors
- Integrated image rendering for robot representation

## Notes
- Ensure that all `.java` files are compiled together as they are interdependent.
- The program uses Java Swing for the GUI, so it must be run in an environment that supports desktop applications.
- The image file `robot.png` must be placed in the correct resource path to display the robot icon correctly on the interface.

