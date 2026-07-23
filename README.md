# Smart Traffic Management System

A Python implementation demonstrating OOP polymorphism using a Smart City traffic control scenario.

## Overview

In a smart city infrastructure, different devices receive the same high-level command (e.g., `activate()`), but each device must respond according to its specific function. 

This project uses **method overriding** and **dynamic method dispatch** to manage various traffic components cleanly—eliminating the need for messy `if-elif-else` type checks.

## Key Features

* **Parent Class (`TrafficDevice`):** Establishes the core interface with an `activate()` method.
* **Child Classes:** Custom behaviors implemented for:
  * `TrafficLight`
  * `SpeedCamera`
  * `PedestrianSignal`
  * `EmergencySiren`
* **Polymorphic Execution:** Devices are stored in a single list and triggered using a unified interface without checking their explicit types.
* **Extensibility:** Demonstrates how easy it is to plug in new devices (like `EmergencySiren`) without touching the existing loop or application logic.
## Author
Mensah Maxwell
EL 162
FOE.41.006.110.25
