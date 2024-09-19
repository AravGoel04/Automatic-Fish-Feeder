# Automatic-Fish-Feeder
The feeder is designed to dispense fish food at regular intervals, ensuring your aquatic pets are well-nourished.

Overview

The Automatic Fish Feeder is an IoT-enabled device designed to automate the feeding process in aquariums and fish farms. By integrating technologies like Arduino, NodeMCU, RTC, and temperature sensors, this feeder provides timely and measured feeding, ensuring optimal fish health while reducing the burden of manual intervention.
Features

    Automated Feeding: Pre-scheduled feeding at intervals using a servo motor.
    Real-Time Clock (RTC): Accurate feeding schedule with backup during power outages.
    Remote Monitoring: Wi-Fi-enabled monitoring and control via mobile or web applications using NodeMCU ESP8266.
    Environmental Monitoring: Tracks water temperature to optimize feeding.
    Alert System: Sends notifications when the feed storage is low.

Hardware Components

    Arduino Uno: Main microcontroller that manages the feeding schedule.
    NodeMCU ESP8266: Provides Wi-Fi connectivity for remote access.
    Servo Motor: Controls feed distribution by rotating at specified intervals.
    RTC (DS3231): Maintains accurate feeding times.
    LCD Display: Displays system status and feeding times.
    Power Supply: Ensures a steady supply of power for all components.

Software Requirements

    Arduino IDE: Used for programming the Arduino and NodeMCU.
    Embedded C: The project uses Embedded C for coding and managing the fish feeder's functionality.

System Architecture

    Arduino Uno controls feeding intervals and manages motor operations.
    NodeMCU ESP8266 provides Wi-Fi connectivity for remote control and monitoring.
    RTC (DS3231) ensures accurate timekeeping for scheduled feeding.
    Servo Motor dispenses the fish feed as per the programmed schedule.
    LCD Display provides real-time feedback on system operations and alerts.

    ![image](https://github.com/user-attachments/assets/0833b50a-ad2b-42b1-a513-1e1fc78264ad)


Installation and Setup

Clone the repository.

    git clone https://github.com/username/automatic-fish-feeder.git

    Open the project in Arduino IDE.
    Upload the code to Arduino Uno and NodeMCU ESP8266.
    Power up the system and configure Wi-Fi credentials for remote monitoring.
    Set up the feeding schedule and monitor environmental factors.

Usage

    Use the LCD display to monitor current feeding schedules and sensor data.
    Connect to the feeder remotely via the web interface for control and updates.
    Set custom feeding intervals based on the fish's dietary needs.

Results

    Improved feeding efficiency with reduced wastage.
    Enhanced fish health due to timely and controlled feeding.
    Remote monitoring and management allow for greater convenience.

Future Enhancements

    Integration of AI for adaptive feeding based on fish behavior.
    Solar-powered operation for increased sustainability.
    Expandable for larger aquaculture systems with multiple tanks.

License

This project is licensed under the MIT License - see the LICENSE file for details.
