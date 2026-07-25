# Android Test App

This is a minimal Android app project that requests Contacts and Location permissions, reads the first contact, and fetches the device's last known location and reverse-geocodes it to display an address.

How to build

- Open the project in Android Studio and let Gradle sync. The project uses Kotlin.
- Run on a device or emulator (emulator needs Play Services for Fused Location).

Notes and limitations

- The app requests runtime permissions for READ_CONTACTS and ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION.
- Reverse geocoding uses Geocoder which may not work on all emulators; test on a device if possible.
- This is a sample/test project—error handling is minimal. Adapt as needed.
