# Indoor Navigation and Live Tracking

<img src="https://forthebadge.com/images/badges/made-with-javascript.svg"> 

https://github.com/user-attachments/assets/cc9f0195-b10c-4e6d-8765-23802076b55b

![Image](https://github.com/user-attachments/assets/22f2f99f-7fd1-4c19-bb35-d767bbd05574)
![Image](https://github.com/user-attachments/assets/5592ebe7-f9ce-468e-8137-0e410425e984)
![Image](https://github.com/user-attachments/assets/1e524add-3c58-464d-9c3c-f4795897fd0b)
![Image](https://github.com/user-attachments/assets/3e91396b-ffa2-4815-beb4-10f0690f9f62)


This project provides a live tracking system for navigating a floor plan, using device motion sensors to automatically rotate the map and track movement within a building. The system allows users to set their starting location, view real-time stats, and see a floor plan with an auto-rotating map based on their device’s orientation.

## Features

- **Set Starting Location**: Select a seat number to set the starting point on the floor plan.
- **Auto-Rotating Map**: The map rotates based on your device's heading, giving a natural, real-time experience.
- **Step Tracking**: Tracks steps as you move, updating your position accordingly.
- **Zoom Controls**: Zoom in and out on the floor plan for a better view.
- **Sensor Data Display**: Shows real-time data like sensor heading, acceleration, and user position.
- **Responsive UI**: Works on mobile devices with motion sensing support.

## How It Works

1. **Floor Plan**: The floor plan image is loaded onto a canvas where the navigation will occur.
2. **Location Selector**: You can input a seat number (e.g., 477, 478, 479) to set a starting location.
3. **Device Orientation**: The device’s orientation is used to auto-rotate the floor plan and adjust the user's direction.
4. **Steps Tracking**: Movement is tracked using accelerometer data, counting steps and adjusting the position.
5. **Zooming**: Zoom functionality is available to allow users to zoom in or out on the floor plan.

## Technologies Used

- **HTML5** and **CSS3** for structure and styling.
- **JavaScript** for dynamic interactivity and handling motion events.
- **Kalman Filter** for smoothing device orientation data.
- **Canvas API** for rendering the floor plan and navigation icon.

## Usage

1. **Select Starting Location**: Enter a seat number from the available options in the input box and click “Set Location”.
2. **Interact with Floor Plan**: Click on the floor plan to set your initial position. Your navigation icon (SVG) will remain fixed, while the floor plan will rotate based on your device’s heading.
3. **Move and Track Steps**: Move around and the app will track your steps, updating your position on the floor plan.

