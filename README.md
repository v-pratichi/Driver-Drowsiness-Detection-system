
Driver Drowsiness Detection is a project developed using Dlib and OpenCV with Python as the backend language.

## Project Logic

This project utilizes the 68 facial landmark detector and face detector from the Dlib library. The 68 facial landmark detector efficiently identifies points on the human face, enabling us to determine whether the eyes are open or closed.


The 68-landmark detector data (.dat) file can be downloaded [here](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2).

## How it Works

1. The screenshot above demonstrates the detection of facial landmarks.
2. We calculate a ratio defined as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
3. This ratio is customizable based on your system to set thresholds for states like sleeping, drowsy, and active.


## Dependencies

- Dlib
- OpenCV

## Usage

1. Clone the repository.
2. Download the 68-landmark detector data file from the provided link.
3. Run the `drowsiness_detection.py` script.

Feel free to explore and modify the code to suit your specific needs. If you have any questions or suggestions, please don't hesitate to reach out.

**Note**: The project contains sample images for demonstration purposes. Please replace them with your own images or remove them before deploying the project.

---

Please make sure to replace the placeholders with actual content like installation instructions, usage examples, and any other relevant information about your project.
