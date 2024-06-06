# Tennis Analysis

## Introduction
This project leverages advanced computer vision techniques to analyze tennis players in video footage, measuring their speed, ball shot speed, and number of shots. Utilizing YOLO for player and ball detection, and CNNs for extracting court keypoints, this project demonstrates the effective application of machine learning to real-world sports analytics.

## Result
The resulting output video looks like this:

![Screenshot Demo](https://github.com/anqitwa/tennis-analysis/blob/main/output_videos/screenshot.png)

## Models Employed
- **YOLO v8:** Primarily utilized for precise player detection.
- **Fine-Tuned YOLO:** Tailored specifically for accurate tennis ball detection.
- **Court Keypoint Extraction:** Leveraging CNNs to identify crucial court keypoints.

Access the trained models here:
- [Trained YOLOV5 Model](https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing)
- [Trained Tennis Court Keypoint Model](https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing)

## Training Resources
- **Tennis Ball Detector Training:** Explore the steps of training the tennis ball detector using YOLO in the notebook: `training/tennis_ball_detector_training.ipynb`.
- **Tennis Court Keypoint Training:** Refer to the training process for the tennis court keypoint extraction model using PyTorch in the notebook: `training/tennis_court_keypoints_training.ipynb`.

## Requirements
Ensure the following dependencies are installed to facilitate seamless execution of the project:
- Python 3.8
- Ultralytics
- PyTorch
- Pandas
- NumPy
- OpenCV
