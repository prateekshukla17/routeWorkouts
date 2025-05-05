# 🏋️‍♂️ RouteWorkouts

## 📌 Features
- Detects user’s current location.

- Interactive map to log workout locations.

- Custom form to enter workout details.

- Saves and loads workouts from local storage.

- Click on workout list to zoom into the map.

- Seamless UI with real-time rendering of workouts on map & list.

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript

- Maps: Leaflet.js

- Storage: LocalStorage (No backend required)

## 🚀 How it Works
On load, app fetches your current location (via browser).
Initializes the map centered at your location.
Loads previously saved workouts from localStorage.
Click anywhere on the map to log a workout.
Fill the workout form and submit.
Workouts appear both on the map and in the list.
Clicking a workout in the list zooms the map to that point.

## 🧪 How to Run Locally
- Step-1
```bash
git clone https://github.com/prateekshukla17/workout-mapper.git
cd workout-mapper
```

- Step-2
Open `index.html` in any modern browser.
No setup or build needed. Fully client-side and lightweight.


## 📌 Note
- Works only on secure origins (https or localhost) for geolocation.
- Make sure location access is enabled in the browser.
