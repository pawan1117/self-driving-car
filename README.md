# Self-Driving Car Simulator 🚗

## Overview
This project is a self-driving car simulation that navigates autonomously using sensor data and a neural network. The car detects road boundaries and obstacles to adjust its movement, aiming to mimic real-world autonomous vehicle behaviors.

The core features include:
- Sensors for detecting surroundings.
- Collision detection to avoid obstacles.
- Directional control based on sensor input.
- Neural network integration for decision-making.
- Customizable car parameters such as speed and sensor range.

## 🛠️ Features
- **Autonomous Movement**: The car moves on its own based on sensor input and neural network predictions.
- **Sensor System**: Simulates multiple sensors around the car for detecting road boundaries and objects.
- **Collision Detection**: Detects when the car is about to hit a boundary or object and adjusts movement accordingly.
- **Transparency Effects**: Visual transparency based on collision proximity for enhanced visualization.
- **Customizable Controls**: Manual overrides allow the user to adjust car direction using keyboard input.

## 🎮 Controls
- **Arrow Keys:** Manually control the car direction.
- **Automatic Mode:** The car will navigate based on sensor input and neural network decisions without manual interference.


https://github.com/user-attachments/assets/f25ba0e8-6f7d-4962-9f9b-8c89e883d342

**Link to the web app:** [Click Here](https://pawan1117.github.io/self-driving-car/) <br/>

## 🧠 Neural Network Details
The neural network is trained to make real-time decisions based on sensor input. It adjusts the car's speed and direction depending on the surrounding environment. The model can be fine-tuned using training data for specific road scenarios.

**Key Components:**
- **Input Layer:** Sensor data (e.g., distance from obstacles).
- **Hidden Layers:** Customizable architecture for processing sensor inputs.
- **Output Layer:** Decides the car's direction (left, right, forward).

## 🛑 Known Issues
- The sensor alignment sometimes differs from the car’s actual direction.
- In certain cases, the car might make incorrect decisions based on sensor noise.

## 🛠️ Future Enhancements
- Improved collision avoidance with more advanced detection algorithms.
- Training improvements for the neural network to enhance accuracy.
- UI controls for dynamically adjusting car parameters (speed, sensor range, etc.).
- Support for multiple vehicles to simulate traffic scenarios.

## 📂 Project Structure
```bash
├── src
│   ├── Car.js                # Core car functionality
│   ├── Sensor.js             # Sensor system for boundary and obstacle detection
│   ├── NeuralNetwork.js      # Neural network for decision-making
│   ├── Road.js               # Simulates road and boundary conditions
│   ├── index.html            # Main HTML file for visualization
│   ├── style.css             # Styling for the car and road
│   └── app.js                # Main script to initialize the car and road
└── README.md                 # Project documentation
<br>

# 🚀 How to Run the Project

## Prerequisites
- Node.js (for running a local development server)
- A modern browser for visualization (Chrome, Firefox, etc.)

## Steps to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/self-driving-car.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd self-driving-car
    ```

3. **Install dependencies (if applicable):**
    ```bash
    npm install
    ```

4. **Start the server:**
    ```bash
    npm start
    ```

5. **Open `index.html` in your browser or use a local server to visualize the simulation.**
```
