# Simple Location Tracker

## App Description:
This is a simple Android application that displays the user's current location on a Google Map. The app allows the user to see their real-time location with a marker and moves the camera to their current position.

## Permissions Used:
- **ACCESS_FINE_LOCATION** – To access the precise GPS location of the device.
- **ACCESS_COARSE_LOCATION** – To access approximate location when GPS is unavailable.
- **INTERNET** – To load Google Maps.

## How GPS Location is Obtained:
The app uses the Fused Location Provider from Google Play Services to get the device's current location. When the app starts, it requests runtime permission for location access. If granted, the app retrieves the last known location and displays it on the map. The map camera moves to the current location, and a marker is added to indicate it.
