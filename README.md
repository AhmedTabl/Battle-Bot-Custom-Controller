# Battle-Bot-Custom-Controller
This project showcases the design and development of a custom-built battle bot controller, specifically tailored for use in combat robotics competitions. The controller is built around the ESP32 microcontroller and leverages NRF24L01 modules for reliable, long-range wireless communication with the battle bot. The system provides precise control over the bot’s movement and weapon systems.

**Key Features:**
- **ESP32 Microcontroller:** The core of the controller, responsible for managing inputs from the user and communicating with the bot via the NRF24L01 module.
- **NRF24L01 Wireless Module:** Facilitates low-latency, long-range communication between the controller and the battle bot, enabling seamless operation over distances up to 100 meters.
- **Joysticks:** Used to control movement and directional inputs, providing precise control during combat.
- **LCD Screen:** A 20x4 LCD display that shows critical real-time data such as battery status, communication strength, and weapon system activity.
- **Power Switches:** Includes three switches for:
- **Main Power:** Controls overall power to the controller.
- **Weapon System:** Toggles the weapon system on/off, sending predefined PWM values to the bot for weapon activation.
- **Radio Module:** Controls the power to the NRF24L01 module, allowing for easy reconfiguration.
- **Modular Design:** The controller is designed to be easily modifiable, allowing for adjustments in power configuration, joystick sensitivity, and more, depending on competition requirements.

**Software Overview:**
- **PWM Control:** Sends precise Pulse Width Modulation (PWM) values to control the motors and weapon systems on the bot.
- **Weapon Activation:** A dedicated switch on the controller enables or disables the weapon system, transmitting a PWM signal of 2000 when active and 0 when inactive.
- **Data Display:** The LCD provides key metrics for the driver, including weapon status and communication reliability.
- **Real-time Feedback:** Ensures real-time control with minimal communication delay, crucial for responsive operation in fast-paced combat scenarios.

**Project Goals:**
- **Reliable Control:** Designed to ensure a stable and reliable connection between the controller and battle bot, even in environments with high wireless interference.
- **Ease of Use:** The interface is designed for ease of use, with intuitive controls and clear feedback on the LCD.
- **Customization:** Built to be easily modifiable for future enhancements and adjustments in various competition scenarios.

This project demonstrates the integration of microcontrollers, wireless communication, and custom electronics to provide a high-performance solution for combat robotics.
