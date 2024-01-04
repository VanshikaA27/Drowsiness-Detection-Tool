



# Drowsiness Detection and Data Collection Tool

## Overview

This Python script serves as both a drowsiness detection system and a data collection tool. It leverages OpenCV to access the webcam, capture images, and label them for training a machine learning model. The collected data is useful for detecting signs of drowsiness in real-time.

## Features

- **Data Collection**: Collects labeled image datasets crucial for training a drowsiness detection model.
- **Real-time Detection**: Provides the functionality to detect signs of drowsiness or fatigue.
  
## Requirements

- Python 3.x
- OpenCV (`cv2`)
- `uuid` library

## Setup

1. **Installation**:

   ```bash
   pip install opencv-python-headless
   ```

2. **Clone Repository**:


3. **Usage**:

   - Set the desired labels and the number of images to collect (`labels` and `number_imgs` variables in the script).
   - Run the script:

     ```bash
     python drowsiness_data_collection.py
     ```

4. **Instructions**:

   - Follow on-screen instructions to collect labeled images for each specified label.
   - Press `q` to stop collecting images for a particular label.

5. **Drowsiness Detection**:

   - For drowsiness detection, utilize the collected data to train a machine learning model (not included in this script).
   - Integrate the trained model with the data collection script for real-time drowsiness detection.

6. **Notes**:

   - Ensure diverse image variations and lighting conditions for a comprehensive dataset.
   - Augment the dataset with various facial expressions and scenarios to enhance model robustness.



---

Feel free to customize this README to better fit your specific use case, add more detailed instructions, or include any additional features or information relevant to the tool's functionality as both a data collection and a detection tool.

