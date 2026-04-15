# Flutter GPS Location App

## Overview

This project is a Flutter application that demonstrates how to access a device’s GPS location using the `geolocator` package. The app retrieves the user's current latitude and longitude after handling necessary permissions.

It highlights how to work with device location services and manage runtime permissions in Flutter.

---

## Features

* Fetch current GPS location (latitude and longitude)
* Handle location service availability
* Request and manage user permissions
* Display real-time location data
* Simple and user-friendly interface

---

## Technologies Used

* Flutter
* Dart
* Geolocator package

---

## Project Structure

* `main.dart`

  * Contains the entire application logic
  * Includes:

    * `MyApp`: Root widget
    * `LocationPage`: Handles location fetching and UI

---

## How It Works

1. The app launches with the LocationPage screen.
2. Initially, a message "Press button" is displayed.
3. When the user clicks "Get Location":

   * The app checks if location services are enabled.
   * It verifies and requests permissions if needed.
   * Handles cases:

     * Permission denied
     * Permission permanently denied
   * If permissions are granted:

     * Retrieves current position using GPS
     * Displays latitude and longitude on the screen

---

## How to Run

1. Install Flutter on your system.
2. Add the dependency in `pubspec.yaml`:

   ```
   dependencies:
     geolocator: ^9.0.0
   ```
3. Configure platform permissions:

   * Android: Add location permissions in `AndroidManifest.xml`
   * iOS: Add location usage description in `Info.plist`
4. Replace the content of `main.dart` with this code.
5. Run the following command:

   ```
   flutter run
   ```
6. Test on a real device for accurate GPS results.

---

## Future Improvements

* Display location on Google Maps
* Track live location updates
* Save location history
* Add reverse geocoding (address from coordinates)
* Improve UI/UX design

---

## Student Information

* Name: Sidharth Tripathi
* Roll Number: 23EACCA047
* Branch: Al
* Batch: BETA
