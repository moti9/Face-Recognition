# Face Recognition Project

This project is designed to capture and recognize faces using OpenCV and Python. It includes two main scripts: `add_face.py` for capturing and saving face data and `face_recognition.py` for recognizing faces. This README provides an overview of the project and instructions on how to use it.

## Prerequisites

Before using the project, make sure you have the following dependencies installed:

- OpenCV (cv2)
- NumPy
- Python 3.x

## Project Structure

The project is structured as follows:

- `add_face.py`: Script for capturing and saving face data.
- `face_recognition.py`: Script for recognizing faces.
- `data/`: Directory for storing data files, including haarcascade XML files, face data, and names.
- `README.md`: This file.

## Usage

### 1. Capture and Save Face Data

Run `add_face.py` to capture and save face data for a specific person:

```bash
python add_face.py
```

- You will be prompted to enter your name.
- The webcam will activate, capturing your face.
- Captured face data (10 samples) will be saved in data/faces.pkl, and your name will be saved in data/names.pkl.

### 2. Face Recognition

Run face_recognition.py to recognize faces using the previously saved data:

```bash
python face_recognition.py
```

- The webcam will activate and attempt to recognize faces based on the saved data.
- If a match is found, the recognized person's name will be displayed.

### Note

- The project saves 10 samples of your face data in data/faces.pkl, along with your name in data/names.pkl.
- Ensure that the haarcascade XML file for face detection is located in the data/ directory.
- You can capture face data for multiple individuals by running add_face.py with their respective names.
- This project is a simple example and can be extended for more advanced face recognition tasks.

Feel free to explore and modify the code to suit your specific use case. Enjoy using this face recognition project!
