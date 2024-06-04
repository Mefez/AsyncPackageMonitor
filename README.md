# Signal Monitor Simulation

## Overview
This project simulates a monitor and multiple devices that send signals to the monitor. The devices and the monitor run in asynchronous threads. Devices send data using sockets, and the monitor counts the signals received from each device. When the user presses a key, the simulation ends, and the monitor prints the number of signals per device.

## Features
- Asynchronous communication between devices and the monitor.
- Devices send signals via sockets.
- Monitor counts and displays the number of signals from each device upon user input.

## Prerequisites
- **C++ Compiler**: Ensure you have a C++ compiler installed.
- **Visual Studio 2022**: This project is set up for Visual Studio 2022.
- **Sockets Library**: Make sure the necessary sockets library is installed and configured.

## Installation
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Mefez/AsyncPackageMonitor.git
   cd AsyncPackageMonitor
2. **Run the Devices**:
        Start the device applications, each in separate terminal windows or instances.

3. **Monitor Signals**:
        The monitor will asynchronously count signals from each device.
        Press any key in the monitor's terminal to end the simulation and display the signal counts.

## Firewall Configuration
**Important Notice**:

This software uses sockets for communication. Firewalls might block socket connections, leading to connectivity issues. To ensure proper functionality:
Add the software to the firewall whitelist:
- Windows Firewall: Go to Control Panel -> System and Security -> Windows Defender Firewall -> Allow an app or feature through Windows Defender Firewall and add your application.
- Other Firewalls: Follow the respective firewall's instructions to add the software to the whitelist.
