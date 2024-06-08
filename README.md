# Real-Time Eye Tracking using Python

This project demonstrates real-time eye tracking using Python, OpenCV, and Dlib. It detects the eyes in a video stream, tracks their movement, and displays the results in real-time.

## Requirements
- Python 3.x
- OpenCV
- Dlib

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/RishiSingh27/Real-Time-Eye-Tracking.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the shape predictor file from Dlib's official website: [shape_predictor_68_face_landmarks.dat](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place it in the project directory.

## Usage

1. Run the `project.py` script:

    ```bash
    python project.py
    ```

2. Adjust the threshold using the trackbar to fine-tune the eye detection.

3. Press 'q' to quit the application.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
