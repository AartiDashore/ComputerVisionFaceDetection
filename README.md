# Computer Vision Face Detection
Real-Time Face Detection (OpenCV)
A simple real-time face detection project using **Python** and **OpenCV**. The program accesses your webcam, detects faces using a Haar Cascade classifier, and draws bounding boxes around them.

## Demo

Faces detected in real time using a webcam feed with green rectangles drawn around each detected face.

## Tech Stack

* Python 3
* OpenCV (`cv2`)
* Haar Cascade Classifier

## Features

* Real-time webcam face detection
* Lightweight and fast
* Clean exit using `q` key or window close button
* Beginner-friendly OpenCV example

## Project Structure

```
.
├── face_detection.py
├── haarcascade_frontalface_default.xml
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install opencv-python
```

3. Download the Haar Cascade file (if not included):

* `haarcascade_frontalface_default.xml`

Place it in the same directory as the script.

## Usage

Run the script:

```bash
python face_detection.py
```

## Controls

* Press **`q`** to quit
* Or close the window using the window close button

## How It Works

1. Captures video from the webcam
2. Converts frames to grayscale
3. Detects faces using a Haar Cascade classifier
4. Draws rectangles around detected faces
5. Displays the processed video in real time

## Notes

* Best results with good lighting
* Works best for frontal faces
* Haar Cascades are fast but less accurate than modern deep-learning approaches

## Future Improvements

* Add eye or smile detection
* Switch to a deep learning model (DNN)
* Save detected face images
* Add FPS counter

## License

This project is licensed under MIT Licence and is intended for educational use.
