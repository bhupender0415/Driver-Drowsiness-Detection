# Driver Drowsiness Detection

This project is a Drowsiness Detection system built with Python. The Drowsiness Detection system is designed to prevent accidents that occur due to drowsiness. It uses a webcam to capture video and then processes the video frames to locate the user's face and eyes. The system then monitors the eyes to detect drowsiness.

The system uses OpenCV, Dlib, and imutils libraries for image processing, and the Dlib library for deep learning based Modules and face landmark detection. The system alerts the user by playing a sound when it detects drowsiness.

## Screenshots

<p><img src="https://github.com/bhupender0415/Driver-Drowsiness-Detection/blob/master/Screenshot/WhatsApp%20Image%202023-12-04%20at%2012.23.31%20AM.jpeg" align="center" height="270"> &nbsp <img src="https://github.com/bhupender0415/Driver-Drowsiness-Detection/blob/master/Screenshot/tanmay.png" align="center" height="270">

<p><img src= "https://github.com/bhupender0415/Driver-Drowsiness-Detection/blob/master/Screenshot/WhatsApp%20Image%202023-12-04%20at%2012.22.53%20AM.jpeg"align="center" height="270"> 

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

## Our contributors

<table>
  <tr>
        <td align="center"><a href="https://github.com/Tanmay-Saxena10"><img src="https://avatars.githubusercontent.com/u/115370358?s=400&u=763dcaa3565639fb8bb9a27e240c83dd473acdce&v=4" width="100px;" alt=""/><br /><sub><b>TANMAY SAXENA</b></sub></a><br />

<td align="center"><a href="https://github.com/bhupender0415"><img src="https://avatars.githubusercontent.com/u/63164983?v=4" width="100px;" alt=""/><br /><sub><b>BHUPENDER SINGH</b></sub></a><br />
<td align="center"><a href="https://github.com/SAM-17-ART"><img src="https://avatars.githubusercontent.com/u/82834807?v=4" width="100px;" alt=""/><br /><sub><b>SATYAM</b></sub></a><br />
</table>

## License

This project is licensed under the terms of the MIT license.
