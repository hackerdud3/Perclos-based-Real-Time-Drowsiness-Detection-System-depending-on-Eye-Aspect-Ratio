# Perclos-based-Real-Time-Drowsiness-Detection-System-depending-on-Eye-Aspect-Ratio
Nearly 30% of road accidents happen due to the driver's drowsiness. This is a Deep Learning model which uses image processing techniques, such as Haar-cascade and Perclos algorithms, to determine the driver's fatigue factor by monitoring him in real-time and can help prevent road accidents by alerting the driver.


Driver Drowsiness Detection :oncoming_automobile:
============

This system monitors drowsiness by detecting the driver's face and sending a drowsiness alert if his eyes have been closed for a certain number of frames. 
The user can configure their own threshold by specifying an EAR ratio and customising the number of frames if they do not want to use the defaults. 

---

## Libraries used:
- `dlib` for the face detection model
- `opencv-python` for drawing frames around the eyes
- `tkinter` for the GUI
- `playsound` to play the alarm
- `scipy` for Euclidean distance calculations


---

## Installation:

**You must have Python 3.6 or higher to run the file.**

- Create a new virtual environment for running the application. You can follow the instructions 
- Navigate to the virtual environment and activate it.
- Install the dependancies using `pip install -r requirements.txt`
- Run the `drowsiness.py` file with `python drowsiness.py`

---
