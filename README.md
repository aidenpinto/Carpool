# Carpool 🚗

A minimalist web application designed to figure out the order in which you pick up your friends. Carpool calculates the most efficient driving route for multiple stops and launches the optimized directions directly into Google Maps.

## Features

* **Route Optimization**: Uses the Open Source Routing Machine (OSRM) to solve this Travelling Salesman Problem.
* **No API Key Required**: Operates without the need for a Google Maps API key or  backend.
* **Clean UI**: Features a responsive, clean interface built with Tailwind CSS.
* **Direct Navigation**: Generates a pre-sorted Google Maps URL for immediate use on mobile and desktop devices.

## Tech Stack

* **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+)
* **Geocoding**: Nominatim (OpenStreetMap)
* **Routing Engine**: OSRM (Open Source Routing Machine)

## Usage

1. **Clone the repository**:
   ```bash
   git clone git@github.com:aidenpinto/Carpool.git```
2.  **Run the application**:
    Open the `index.html` file in any web browser.

3.  **Input Addresses**:
    Enter your starting point, the addresses of the friends you need to
    pick up, and your final destination.

4.  **Navigate**:
    Click the action button to calculate the fastest order. The
    application will automatically open a new tab with the optimized
    route in Google Maps.

## Licence

MIT Licence. Feel free to use, modify, and distribute.
