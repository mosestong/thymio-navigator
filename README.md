# Thymio Navigator

## Overview

This project involved designing and implementing an **obstacle avoidance program** for the **Thymio II robot** to navigate a complex timed course.

## Technical Details

*   **Robot Platform:** Thymio II
*   **Programming Language:** Aseba
    *   *Note on Programming Language:* Aseba is an event-based scripting language designed for the Thymio platform. It supports core programming functionalities (variables, loops, conditional execution, etc.) necessary for implementing the robot's behaviour.
*   **Core Algorithm:** The program enables the robot to autonomously follow a path, avoid obstacles, and interact with barcodes. Using its sensors, the robot navigates through the course, stops when it encounters obstacles, and reads barcodes to determine its next action. The robot's behaviour is managed through a set of states that control movement, tuning, and recovery, allowing it to operate independently.
*   **Code Structure:** The entire program is contained within a single `.aseba` file, as required for compilation and direct upload to the Thymio II robot.

## Setup & Execution

To run this program, you would need:
1.  A Thymio II robot.
2.  Aseba Studio software.
3.  Load `thymio_navigator.aseba` onto the robot via Aseba Studio.
