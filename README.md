<div align="center">

# **Improvised Robot Car**

*General Information:*

![Last Commit](https://img.shields.io/badge/last%20commit-5%2F30%2F2025-orange)

</div>

## Overview
An improvised circuit consisting of an LM339-N chip that controls the overall logic of the car that passes input from three light sensors on the front of the car into an external logic circuit that then routes its respective logic back into MOSFETs on the original circuit in order to manage motor control. The external unit utilizes a quad NAND gate chip that provides the motors with power when circuit logic is met. For my purposes, I simplified the logic for my external circuit pushing power depending on simply the left and center sensor. The logic for the external circuit is as follows: L<sub>W</sub> = L<sub>S</sub>' and R<sub>W</sub> = L<sub>S</sub>' + C<sub>S</sub>'
### Purpose
The circuit was meant to act as a testing ground for the my classmate's own external logic circuits in my IB Computer Science course during our unit on circuits. I devised the original circuit controlling overall logic that then allowed for my classmates to plug in their own circuits and complete the car's functionality.

## Design
The overall circuit is shown below in Figure 1 with the needed input lines for the external circuit shown on the left handside in order. My car did not contain the switch seen in the top of the car schematic, as well as I only utilized the input lines for each sensor and the wheels, the VCC and Ground were included in other parts of the circuit.<br>
The external logic circuit was based upon the gates shown below in Figure 2. For my design, I only utilized three of the gates, using two the NOT the left and center sensor, and then another to combine each of NOT outputs.
### Figure 1: Schematic
![Schematic](https://github.com/willferrens/robot-car/blob/main/Schematic.png?raw=true "Robot Car Schematic")
### Figure 2: External Logic Circuit
![Quad NAND Gate Chip](https://github.com/willferrens/robot-car/blob/main/NAND%20schematic.png?raw=true "Quad NAND Gate Chip")

## Product
The overall product was originally based upon a design with two wheels running six volt motors, but was changed two nine volt motors running tank treads--requiring more voltage to be alloted to the circuit.

### Figure 3: Top View of Robot Car
![Top View of Robot Car](https://github.com/willferrens/robot-car/blob/main/robot-car_top.jpg?raw=true "Top View of Robot Car")
### Figure 4: Side View of Robot Car
![Side View of Robot Car](https://github.com/willferrens/robot-car/blob/main/robot-car_side.jpg?raw=true "Side View of Robot Car")
