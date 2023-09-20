# Real-Time Body Movement Detection with TensorFlow

This repository contains a ReactJS application that utilizes the TensorFlow library to capture real-time body movements with the assistance of artificial intelligence.

## How It Works

The application utilizes the pre-trained PoseNet model provided by the TensorFlow.js library to detect real-time body poses from a webcam connected to the device.

Based on the detected poses, the application uses a neural network to classify the movement into one of the following categories: squat, push-up, or plank.

The application's interface displays a webcam video feed, along with a list of the user's performed movements and a count of how many repetitions have been completed for each of the movements.

## Installation and Usage

To run the application locally, follow these steps:

- Clone this repository to your local machine using **`git clone https://github.com/omatheusribeiro/real-time-pose`**.

- Navigate to the directory created by the repository clone using **`cd real-time-pose`**.

- Install the project dependencies using **`npm install`**.

- Start the application using **`npm start`**.

- Access the application in your web browser by navigating to **`http://localhost:3000`**.

## Contribution

This project was developed as part of an academic assignment and is not actively maintained. However, if you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the BSD 3-Clause "New" or "Revised" License - see the LICENSE file for details.
