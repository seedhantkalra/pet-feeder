# Remote Pet Feeder

## Overview

The Remote Pet Feeder is an innovative application that allows users to remotely dispense food for their pets through mobile control. The application integrates hardware control through Python scripts and provides a user-friendly interface for managing the feeding process. It also features a camera module that allows users to monitor their pets in real time.

## Features

- **Remote Food Dispensing:** Control the food dispenser remotely using the mobile app.
- **Real-Time Monitoring:** View live footage from the camera integrated with the feeder.
- **User Authentication:** Secure login and authentication using Firebase.
- **Cross-Platform:** Compatible with both iOS and Android devices.
- **Scalable Backend:** Built with Node.js and Express, providing a scalable backend infrastructure.


## Usage

1. **Sign In:**
   - Sign in using the mobile app with your credentials.

2. **Access the Feeder:**
   - Navigate to the camera page to monitor your pet.
   - Use the control interface to dispense the desired amount of food.

3. **Monitor Pet:**
   - View live footage of your pet through the integrated camera.

## Project Structure

- **camera.py:** Handles the camera module for real-time monitoring.
- **stepper.py:** Controls the stepper motor responsible for dispensing the food.
- **server.js:** Node.js server that manages API requests and executes Python scripts.
- **firebase.js:** Configuration for Firebase authentication and database.
- **App.js:** Main React component managing the application's routing and layout.
- **index.css:** Contains the styles used across the application.

