## Pose Estimation System with MoveNet

### Overview
This project leverages Google's MoveNet algorithm to develop a pose estimation application using a single camera setup. The system tracks human movements and collects kinematic data for exercise analysis.

### Features
- **Single Camera Setup**: Simplified UI for capturing movement data.
- **MoveNet Integration**: Utilizes TensorFlow Lite MoveNet for real-time pose estimation.
- **Kinematic Data Collection**: Tracks key joint angles during exercises.
- **Self-Occlusion Handling**: Reduces data loss when joints are obscured.
- **Data Filtering**: Incorporates ML algorithms to filter and correct false data.

### Structure
- **Main Notebook**: Manages the UI and main application flow.
- **Exercise Logic Module**: Contains functions and exercise definitions for modularity.

### Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the main notebook to start the application.

### Future Work
- Add more exercises.
- Enhance self-occlusion handling.
- Improve data filtering algorithms.

Feel free to contribute and make this system better!
