# Automated_Testing_Framework
This repository contains a Python-driven automated testing framework designed to control and test the GPIO pins of an STM32F401CC ARM kit (Blackpill). The framework is implemented using Python, and it interfaces with the microcontroller via UART to send control commands and receive responses.

Features
GPIO Control: The framework allows users to control the state of the GPIO pins on the STM32F401CC kit by sending specific UART commands. This includes setting pins to high or low states and reading their current states.
Automated Test Scripts: Python scripts automate the testing process by sending predefined sequences of UART bytes to the microcontroller, checking the responses, and logging the results.
Modular Design: The framework is designed with modularity in mind, allowing easy expansion and customization for different test cases and hardware configurations.
VS Code Integration: The project is set up for development and testing within Visual Studio Code, leveraging its powerful editing and debugging capabilities.
Getting Started
Prerequisites
Hardware:

STM32F401CC ARM kit (Blackpill)
UART-to-USB adapter for communication between the microcontroller and the host PC
Software:

Python 3.x
Visual Studio Code
Required Python packages 
