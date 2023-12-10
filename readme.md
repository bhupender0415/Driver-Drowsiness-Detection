# Driver Drowsiness Detection

This project is a Drowsiness Detection system built with Python. The Drowsiness Detection system is designed to prevent accidents that occur due to drowsiness. It uses a webcam to capture video and then processes the video frames to locate the user's face and eyes. The system then monitors the eyes to detect drowsiness.

The system uses OpenCV, Dlib, and imutils libraries for image processing, and the Dlib library for deep learning based Modules and face landmark detection. The system alerts the user by playing a sound when it detects drowsiness.

## Screenshots

![WhatsApp Image 2023-12-04 at 12 23 31 AM](https://github.com/bhupender0415/Driver-Drowsiness-Detection/assets/63164983/d330aed6-4143-45e1-8333-f82b3fb96bfe)



![Screenshot 2023-12-05 201419](https://github.com/bhupender0415/Driver-Drowsiness-Detection/assets/63164983/7c03a0db-984d-41ac-8a6b-86cf5d4e82a8 "Drowsiness detected")

## Dependencies

The project uses the following libraries:

- OpenCV: For basic image processing functions.
- Numpy: For array related functions.
- Dlib: For deep learning based Modules and face landmark detection.
- imutils: For basic operations of conversion.
- mediapipe: For media processing.
- playsound: For playing sound.
- time: For time-related tasks.

## Installation

To install the dependencies, run the following command:

```bash
pip install opencv-python numpy dlib imutils mediapipe playsound
```

## Usage

To run the program, navigate to the directory containing `DrowsinessDetection.py` and run the following command:

**``python DrowsinessDetection.py``**

When the program is running, it will display two windows: one showing the video capture from the webcam, and the other showing the result of the face detector. The program will run until you press the ESC key.

## Contributing

Contributions are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the terms of the MIT license.
