# Home-Automation
**Home Automation Bot**
Home Automation Bot is a chatbot specifically designed to assist users with controlling and managing smart home devices. By integrating data from various home automation systems and protocols into a large language model (LLM), this chatbot provides seamless control over connected devices such as lights, thermostats, security systems, and appliances.

**Features**
Interactive chatbot interface for home automation control.
Compatibility with a wide range of smart home devices and protocols.
Personalized automation routines and device control based on user preferences.
Real-time updates and monitoring of device statuses.
Voice control integration for hands-free operation.
Installation
To get started with Home Automation Bot, follow these steps:

**Clone the repository:**
git clone https://github.com/yashbhai0456/home-automation-bot.git
cd HomeAutomationBot

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the chatbot by typing or speaking your home automation commands (e.g., "Turn on the living room lights," "Set the thermostat to 72°F," or "Lock the front door").

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
