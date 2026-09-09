# Traffic Light Controller – Logisim

A digital logic simulation of a simple traffic light control system designed in **Logisim**. The project demonstrates the principles of sequential and combinational circuit design by combining logic gates, flip-flops, and timing mechanisms to simulate the operation of a real-world traffic light.

## Overview

This project was developed to explore the design and implementation of a basic sequential digital system using Logisim.

The simulated traffic light controller manages the different states of a traffic light and transitions between them according to a predefined sequence. The system demonstrates how digital logic components can be combined to create a functional control system.

The project provides a visual and interactive way to understand concepts such as:

* Sequential circuit design
* Combinational logic
* Flip-flops and memory elements
* Logic gates
* Clock signals and timing
* State transitions
* Digital system integration

## Objectives

The main objectives of the project were to:

* Design a functional traffic light control system using digital logic.
* Apply principles of sequential circuit design.
* Understand how flip-flops can be used to store system states.
* Implement combinational logic for controlling outputs.
* Use timing and clock signals to control state transitions.
* Integrate multiple digital components into a single working system.
* Simulate and visually observe the behavior of the circuit in Logisim.

## Technologies & Tools

* **Logisim** – Digital logic circuit simulation
* **Logic Gates** – AND, OR, NOT and other required gates
* **Flip-Flops** – State storage and sequential logic
* **Clock** – Timing and state transitions
* **Combinational Circuits** – Output control and logic

## System Design

The traffic light controller is based on a sequence of predefined states. Each state represents a specific configuration of the traffic light outputs.

The circuit combines:

1. **Clock signal** – Provides the timing mechanism for the system.
2. **Flip-flops** – Store the current state of the traffic light controller.
3. **Combinational logic** – Determines the next state and controls the outputs.
4. **Logic gates** – Implement the required Boolean logic.
5. **Traffic light outputs** – Represent the current state of the simulated traffic light.

### State Transitions

The controller follows a predefined sequence of traffic light states. At each clock transition, the system moves to the next state according to the implemented logic.

This allows the circuit to reproduce the basic behavior of a real-world traffic light system within the Logisim simulation environment.

## Simulation

The circuit can be opened and simulated directly in Logisim.

### Main Circuit

![Traffic Light Controller](screenshots/traffic_light_overview.png)



## Concepts Demonstrated

This project demonstrates practical applications of several digital design concepts:

* Boolean logic
* Logic gates
* Sequential circuits
* Combinational circuits
* Flip-flops
* State machines
* Clock-based timing
* Digital system simulation

##  How to Run

1. Install **Logisim** or **Logisim Evolution**.
2. Clone or download this repository.
3. Navigate to the `circuit` folder.
4. Open `traffic_light_controller.circ` in Logisim.
5. Start the simulation using the clock.
6. Observe the traffic light states and their transitions.

## Author

**Hena Šehović**

Project for course Digital Design
International University of Sarajevo

