# Automatic Attendance System

A simple automatic attendance system that marks attendance based on the user's location. It checks if the user's current location matches a predefined location and marks them present if the match is successful.

Features

- Gets user’s real-time location
- Compares it with a predefined location for attendance
- Marks attendance if the user is within the acceptable range
- Built with Python for backend logic and HTML for the frontend interface

Technologies Used

- **Python** - Backend logic and location processing
- **HTML** - Frontend interface
- **Geolocation API** - To retrieve user location from the browser

# How It Works

1. The user accesses the attendance system via a browser.
2. The system requests the user's location using the browser’s Geolocation API.
3. The location is sent to the Python backend.
4. The backend checks if the location is within range of the predefined attendance point.
5. If it matches, attendance is marked.
