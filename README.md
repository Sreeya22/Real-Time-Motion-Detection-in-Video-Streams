# Real-Time Motion Detection in Video Streams

This project implements a real-time motion detection system using OpenCV and Python. It utilizes background subtraction techniques to identify and highlight moving objects in video frames, providing a simple yet effective way to monitor activity.

## Features

- **Background Subtraction**: Isolates moving objects by subtracting the background.
- **Noise Reduction**: Applies erosion to reduce noise in the foreground mask.
- **Bounding Box Visualization**: Draws bounding boxes around detected motion areas for easy visualization.
- **Real-Time Processing**: Processes video frames in real-time for immediate feedback.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   Ensure you have Python installed, then install the required libraries using pip:
   ```bash
   pip install opencv-python moviepy numpy
   ```

## Usage

1. Place your input video file (e.g., `home_dog.mp4`) in the project directory.
2. Modify the `input_video` variable in the code to point to your video file.
3. Run the script:
   ```bash
   python motion_detection.py
   ```

4. The output video with detected motion will be saved in the same directory.

## Example

After executing the program, the detected motion areas will be highlighted with red bounding boxes, demonstrating the system's ability to track moving objects in the video.
