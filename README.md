# my-freertos-lab
This repository is an industry-oriented FreeRTOS labs with practical 
examples, real-world use cases, debugging techniques, and RTOS design 
concepts for my reference.

Why RTOS [Real Time Operating System]?
Answer
Most of embedded products were built using a simple infinite loop.
Codebase Hint: while(1) or while(true)
This is a Super Loop Architecture.
Some Examples:
    - Flashing of LEDs with a fixed pattern
    - Temperature Loggers System
    - Simple Motor Controller
which comes unders category of small products.

Now think about Modern IoT Node has following responsibities:
    - Read sensors data
    - WiFi Communication
    - MQTT Communication
    - OTA Update
    - Data Logging
    - Watchdog Monitoring
    - Daignostics
Managing these many activities inside single loop quickly introduces 
software complexity and becomes difficult to maintain, debug and 
scale.

RTOS has a mechanism to:
    - Run multiple activities independently
    - Assign priorities to activities
    - Meet timing deadlines
    - Improve software maintainability, reliability and scalability

