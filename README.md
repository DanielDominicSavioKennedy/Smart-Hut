# Smart-Hut Home Switch Automation

This repository contains a project for automating home switches using a website interface and a NodeMCU cluster. The project enables users to control and monitor various switches and appliances in their home remotely.

## Features

- Web-based user interface for controlling home switches
- Real-time monitoring and status updates of switches and appliances
- Supports multiple switch clusters for different areas of the home
- Provides scheduling options for automated switching
- Enables manual control of switches through the website interface
- Responsive design for seamless usage on different devices

## Installation

To set up the Smart-Hut Home Switch Automation project, follow these steps:

### Hardware Setup

1. Gather the required hardware components:
   - NodeMCU development boards
   - Switches and relays
   - Jumper wires
   - Power supply
   - Internet connection
   - Relay

2. Connect the switches and relays to the NodeMCU development boards using jumper wires. Ensure the proper electrical connections and take necessary safety precautions.

3. Set up the NodeMCU cluster by connecting the NodeMCU development boards to your local network and configuring them to communicate with each other.

### Software Setup

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/smart-hut-switch-automation.git
   ```

2. Change into the project directory:

   ```bash
   cd Smart-Hut
   ```

3. Deploy the website files to a web server of your choice. Ensure that the web server supports hosting static files.

4. Flash the NodeMCU firmware onto each NodeMCU development board. You can use the Arduino IDE or any other suitable tool for this purpose. Make sure to configure the firmware with the necessary libraries and dependencies for your hardware setup.

5. Upload the provided NodeMCU sketch (`.ino` file) to each NodeMCU board. Update the sketch with your Wi-Fi credentials, IP address or hostname of the web server, and other configuration parameters.

## Usage

1. Connect the NodeMCU cluster to the power supply and ensure they are connected to your local network.

2. Open the website in a web browser by visiting the URL or IP address of the web server.

3. Use the website interface to control the switches and appliances. You can toggle switches on/off, monitor their status, and schedule automated switching.

4. Access the website from any device with a web browser, including smartphones, tablets, and computers, to control your home switches remotely.

## Customization

You can customize the Smart-Hut Home Switch Automation project by modifying the following files:

- `index.html`: This file contains the configuration parameters for the website interface. Update the IP addresses or hostnames of the NodeMCU cluster, as well as any other desired customization options.

- mcu_cluster (`.ino` file): Modify the sketch to suit your hardware setup and requirements. You can add more switches, implement additional functionality, or integrate with other devices or platforms.

## Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the existing coding style and guidelines.


## Acknowledgments

- This project is made possible by the contributions of the open-source community and the availability of NodeMCU development boards.

- The web interface is built using HTML, CSS, and JavaScript, with various libraries and frameworks
