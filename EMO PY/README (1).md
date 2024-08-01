# Expression Finder

Expression Finder is a Python application that utilizes computer vision and deep learning techniques to detect emotions in a video stream or a video file. It combines the power of YOLO object detection for identifying persons in a video frame and DeepFace for analyzing facial expressions to determine the dominant emotion.

## Features

- Detects and labels emotions including anger, disgust, fear, happiness, sadness, surprise, and neutral.
- Provides real-time visualization of emotions overlaid on the video feed.
- Calculates and displays the accuracy percentage of emotion detection.
- Identifies the most frequently occurring emotion in the video.

## Installation

1. Clone this repository to your local machine:

``
git clone https://github.com/LILTIMOTHY64/Emo-py.git
``


2. Install the required dependencies using pip:
``
pip install -r requirements.txt
`` 

3. Download the pre-trained YOLO weights file (`yolov5nu.pt`) and place it in the project directory.

## Usage

1. Run the application:

``
python User Interface.py
``

2. You will be prompted to enter the pathway for the video file or choose to use the camera.
3. Press 'Q' to exit out of the video frame.
4. After the analysis is completed, the most repeated emotion in the video will be displayed.

## Dependencies

- [OpenCV](https://opencv.org/)
- [PySimpleGUI](https://pysimplegui.readthedocs.io/)
- [DeepFace](https://pypi.org/project/deepface/)
- [Ultralytics YOLO](https://github.com/ultralytics/yolov5)

## Contribution

Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or create a pull request.


## Acknowledgements

- YOLOv5 implementation by Ultralytics: https://github.com/ultralytics/yolov5
- DeepFace library: https://pypi.org/project/deepface/
- PySimpleGUI library: https://pysimplegui.readthedocs.io/
