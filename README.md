# my-freertos-lab
This repository contains industry-oriented FreeRTOS labs with practical
examples, real-world use cases, debugging techniques, and RTOS design
concepts for my reference.

## Why RTOS (Real-Time Operating System)?

Most embedded products were built using a **simple infinite loop**. This is
called a **super loop architecture**.

Codebase hint: `while (1)` or `while (true)`

Some examples of small products using a super loop:
- Flashing LEDs with a fixed pattern
- Temperature logger system
- Simple motor controller

Now think about a modern IoT node. 
It has to:
- Read sensor data
- Communicate over Wi-Fi
- Communicate using MQTT
- Perform OTA updates
- Log data
- Monitor a watchdog
- Run diagnostics

Managing all these activities inside a single loop quickly increases
software complexity and makes the system difficult to maintain, debug,
and scale.

An RTOS provides a mechanism to:
- Run multiple activities independently
- Assign priorities to activities
- Meet timing deadlines
- Improve software maintainability, reliability and scalability



