# Urdu Sign Language Recognition Using Ensemble Models

This project implements a real-time Urdu sign language recognition system using an ensemble of deep learning models. The system predicts the Urdu alphabet sign shown in a live video feed and displays predictions from multiple models along with an ensemble result using majority voting.Projcet also applied a traditional method using machine learning along with processing on the dynamic data.

## Features

- **Real-Time Prediction**: Captures live video feed from the camera and detects hand signs.
- **Ensemble Learning**: Combines predictions from three models (EfficientNet, MobileNetV2, and MobileNetV3) to provide a robust final prediction.
- **On-Screen Visualization**: Displays individual model predictions and the ensemble result directly on the live video feed.

## Models Used

1. EfficientNet
2. MobileNetV2
3. MobileNetV3

## Installation

### Prerequisites

1. Python 3.8+
2. A system with a webcam for capturing live video feed.

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/MinahilSiddiqui/Urdu Sign Language Dectection.git
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Place your trained models in the project directory with the following names:
    - `efficientnet_urdu_alphabets.keras`
    - `mobilenet_v2_model.pkl`
    - `saved_mobilenetv3_model.keras`

## Usage

1. Start the application. The live video feed will appear on the screen.
2. Place your hand inside the green box and press **`c`** to capture an image for prediction.
3. The predictions from individual models and the ensemble result will be displayed on the screen and in the console.
4. Press **`q`** to quit the application.

## Project Structure

