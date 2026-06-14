# Womens Safety and Emergency Alert System for Two Wheelers

## Project Overview

This project is designed to improve the safety of women riders during emergency situations. The system is installed on a two-wheeler and continuously monitors user authentication and emergency conditions. It uses biometric verification, location tracking, image capture, and GSM communication to provide quick assistance when needed.

The system is built using ESP32 as the main controller and integrates multiple modules such as a fingerprint sensor, GPS module, GSM module, ESP32-CAM, keypad, LCD display, and buzzer.

---

## Objectives

* Improve women's safety during travel.
* Prevent unauthorized vehicle usage.
* Send emergency alerts with location information.
* Capture images during emergency situations.
* Provide quick communication with family members or emergency contacts.

---

## Features

* Fingerprint-based user authentication
* OTP verification through keypad
* GPS location tracking
* GSM SMS alert system
* Emergency buzzer alert
* ESP32-CAM image capture
* LCD status display
* Real-time emergency notification

---

## Components Used

* ESP32 DevKit
* AS608 Fingerprint Sensor
* NEO-6M GPS Module
* SIM800A GSM Module
* ESP32-CAM
* 16x2 LCD Display
* 4x4 Keypad
* Buzzer
* Power Supply

---

## System Working

### Step 1: User Authentication

The rider places a finger on the fingerprint sensor. The system compares the fingerprint with the stored fingerprint database.

* If the fingerprint matches, the user is authenticated.
* If the fingerprint does not match, access is denied.

### Step 2: OTP Verification

After successful fingerprint verification, the system requests an OTP through the keypad.

* Correct OTP allows further access.
* Incorrect OTP generates a warning.

### Step 3: Normal Operation

The rider can use the vehicle normally after successful authentication.

The LCD continuously displays system status messages.

### Step 4: Emergency Activation

During an emergency, the user can activate the alert system.

Once activated:

* The buzzer starts producing an alert sound.
* GPS module obtains the current location.
* ESP32-CAM captures images of the surroundings.
* GSM module sends an SMS alert.

### Step 5: Alert Notification

The SMS contains:

* Emergency alert message
* GPS coordinates
* Google Maps location link
* User information

The message is sent to predefined emergency contacts.

### Step 6: Evidence Collection

The captured images are stored locally and can be used later as evidence if required.

---

## Advantages

* Fast emergency response
* Improved rider safety
* Biometric authentication
* Real-time location tracking
* Easy to use
* Low-cost implementation
* Suitable for smart transportation applications

---

## Applications

* Women safety systems
* Smart motorcycles
* Personal security devices
* Emergency response systems
* Smart transportation solutions

---

## Repository Structure

* ESP32_Main_Controller
* ESP32_CAM
* Fingerprint_Enrollment
* Fingerprint_Verification
* Circuit_Diagram
* Project_Report
* Images
* Documentation

---

## Future Enhancements

* Mobile application integration
* Cloud data storage
* AI-based threat detection
* Live video streaming
* Voice activation support
* Automatic accident detection

---

## Developed Using

* Arduino IDE
* ESP32 Platform
* Embedded Systems
* IoT Technologies
