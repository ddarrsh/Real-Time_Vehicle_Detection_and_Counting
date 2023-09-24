# Real-Time_Vehicle_Detection_and_Counting
Description: This repository hosts Python code for real-time vehicle detection and counting using computer vision. The code utilizes OpenCV and NumPy to process video input, detect vehicles, and display their count in real-time. For detailed usage instructions and configuration options, please refer to the accompanying README file.


```markdown
# Real-Time Vehicle Detection and Counting

## Description
This repository contains Python code for a real-time vehicle detection and counting system using computer vision. The code utilizes OpenCV and NumPy to process video input and detect vehicles in a streaming video source or a video file.

The key features and components of this code include:
- Background Subtraction
- Contour Detection with customizable width and height thresholds
- Centroid Tracking
- Real-Time Visualization with bounding boxes and centroids
- Configuration Options for easy adaptation to different scenarios
- Support for various video sources, including webcam input and video files

## Installation
Before running the code, you need to install the required Python modules. You can use `pip` to install them:

```bash
pip install opencv-python numpy
```

## Usage
1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/real-time-vehicle-detection.git
cd real-time-vehicle-detection
```

2. Make sure you have a video source ready, such as a webcam or a video file.

3. Run the main Python script:

```bash
python vehicle_detection.py
```

4. The application will open a window displaying the video feed with vehicle detection and counting. Press the 'Esc' key to exit the application.

## Configuration
You can customize the detection parameters in the `vehicle_detection.py` script to suit your specific needs. Modify the following variables as necessary:
- `min_contour_width`: Minimum width of a valid contour
- `min_contour_height`: Minimum height of a valid contour
- `offset`: Detection line offset
- `line_height`: Height of the detection line on the screen
