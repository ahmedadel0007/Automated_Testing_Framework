This repository hosts a Python-based automated testing framework designed specifically for controlling and testing the GPIO pins on an STM32F401CC ARM kit (Blackpill). The framework utilizes Python to interact with the microcontroller via UART, enabling the sending of control commands and the reception of responses.

Features
-> GPIO Control: Effortlessly manage the state of GPIO pins on the STM32F401CC kit by sending precise UART commands. This functionality includes setting pins to high or low states and querying their current status.
-> Automated Test Scripts: Automate your testing processes with Python scripts that transmit predefined UART command sequences to the microcontroller. The framework verifies responses and logs the results for analysis.
-> Modular Design: Built with flexibility in mind, the framework's modular architecture allows for easy expansion and customization, making it adaptable to various test scenarios and hardware configurations.
-> VS Code Integration: The project is configured for seamless development and testing within Visual Studio Code, leveraging its robust editing and debugging features.
Getting Started
Prerequisites
Hardware:

STM32F401CC ARM Kit (Blackpill): The development board used for GPIO testing.
UART-to-USB Adapter: Facilitates communication between the STM32F401CC microcontroller and your PC.
Software:

Python 3.x: Ensure that Python 3.x is installed on your system. Download it from the official Python website.
Visual Studio Code: Download and install this powerful code editor from the Visual Studio Code website.
Required Python Packages:
Install necessary Python packages using pip. A requirements.txt file is included for convenience:

Copy code
pyserial
Install the packages by running:

bash
Copy code
pip install -r requirements.txt
Setting Up
Clone the Repository:

Clone this repository to your local machine:

bash
Copy code
git clone <repository-url>
cd Automated_Testing_Framework
Install Dependencies:

Navigate to the project directory and install the required packages:

bash
Copy code
pip install -r requirements.txt
Configure UART Communication:

Ensure proper connection and configuration of your UART-to-USB adapter. Adjust UART settings in your Python scripts to match your hardware setup.

Open in Visual Studio Code:

Launch Visual Studio Code and open the project directory for development and testing.

Run Automated Tests:

Execute the provided Python scripts to begin testing. The scripts will interact with the microcontroller and log the results:

bash
Copy code
python test_script.py
Review Test Results:

Examine the output logs to review the results of your GPIO tests. The logs will provide details on the responses and any issues encountered.

Additional Information
Modular Expansion: Customize and extend the framework to accommodate different test cases and hardware configurations as needed.
Documentation: For more detailed usage instructions and customization guidelines, refer to the project's documentation and in-code comments.
