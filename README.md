# Drowsiness-Detection-Tool

# Drowsiness Detection Data Collection Tool

## What is this?

This Python script helps collect image data from a webcam for a drowsiness detection system. It's designed to capture images associated with specific labels, which can be used to train a machine learning model to detect signs of drowsiness.

## How does it work?

- **Setup**: The script initializes the webcam and prompts you to collect images for each label specified in the `labels` list.
  
- **Data Collection**: 
  - It captures several images for each label (`number_imgs` times).
  - Each image is uniquely named with the label and a UUID for later use in training.
  
- **Usage**:
  - Run the script and follow the on-screen instructions to collect images for each label.
  - Press 'q' to stop collecting images for a specific label.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- `uuid` library

## How to Use

1. **Install Dependencies**:
   - `pip install opencv-python-headless`

3. **Usage**:
   - Modify the script to set `labels` and `number_imgs`.
   - Run the script: `python drowsiness_data_collection.py`

4. **Tips**:
   - Ensure good lighting and diverse angles for better model training.
   - Consider capturing various facial expressions and environmental conditions for a robust dataset.
