# Drowsiness and Yawning Detection

This project detects drowsiness and yawning in real-time using a webcam feed. It alerts the user when signs of drowsiness or yawning are detected, helping to prevent accidents especially during activities such as driving or working for long hours.

## Features

- Real-time detection of drowsiness and yawning
- Sound alerts for drowsiness detection
- Visual alerts for yawning detection
- Simple and intuitive interface

## Requirements

- Python 3.x
- OpenCV
- dlib
- imutils
- scipy
- pygame

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/Techy7795/Drowsiness-Detection.git
    ```

2. Download the dlib shape predictor model (`shape_predictor_68_face_landmarks.dat`) from [here](https://github.com/davisking/dlib-models/raw/master/shape_predictor_68_face_landmarks.dat.bz2) and place it in the `models` directory.

## Usage

1. Run the `detection.py` script:

    ```
    python detection.py
    ```

2. The webcam feed will open, and the application will start detecting drowsiness and yawning in real-time.

3. Press 'q' to quit the application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/new-feature`)
6. Create a new Pull Request

## Acknowledgements

- [dlib](https://github.com/davisking/dlib) for face detection and facial landmark prediction
- [imutils](https://github.com/jrosebr1/imutils) for image processing utilities
- [pygame](https://www.pygame.org/) for playing sound alerts
- [OpenCV](https://opencv.org/) for computer vision and image processing
