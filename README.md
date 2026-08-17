# Face and Object Detection

This project performs **face detection and object detection** using **YOLOv8 and OpenCV**.

The project can detect faces and different objects from images and real-time webcam video.

## Features

* Face detection using a YOLO-based face detection model
* Object detection using YOLOv8
* Detection on images
* Real-time detection using a webcam
* Displays bounding boxes and labels for detected objects

## Technologies Used

* Python
* OpenCV
* YOLOv8
* Jupyter Notebook

## Project Structure

```text
Face-and-object-Detection/
│
├── Face Detection in Images.ipynb
├── Face Detection in Live Videos.ipynb
├── code1.ipynb
│
├── demo.jpg
├── demo1.jpg
├── demo2.jpg
├── demo3.jpg
├── demo4.jpg
├── demo5.jpg
├── demo6.jpg
│
├── README.md
└── .gitignore
```

## Installation

Install the required libraries:

```bash
pip install opencv-python ultralytics jupyter
```

Start Jupyter Lab:

```bash
jupyter lab
```

Then open the notebooks and run the cells.

## How to Use

### Image Detection

Open the image detection notebook and provide an image as input. The model will detect faces and objects and display the results with bounding boxes.

### Live Video Detection

Open the live video detection notebook to perform real-time detection using your webcam.

## Sample Images

The project includes sample images for testing the detection models. You can also use your own images.

## Model Files

The project uses YOLO model weights for face and object detection. The `.pt` model files are excluded from the repository using `.gitignore` and should be downloaded separately before running the project.

## Author

**Hemanth Love**
