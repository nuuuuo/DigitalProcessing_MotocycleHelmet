
# Object Detection and Helmet Classification

This project involves real-time object detection and helmet classification using a combination of OpenCV, Mediapipe, and a pre-trained model. The script captures video frames, detects persons and motorbikes, and classifies the presence of helmets on detected persons using a pre-trained helmet detection model.

## Getting Started

To run the project, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/object-detection-helmet-classification.git
   cd object-detection-helmet-classification
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the necessary model files:

   - MobileNet SSD model files: `'MobileNetSSD_deploy.prototxt.txt'` and `'MobileNetSSD_deploy.caffemodel'`
   - Pre-trained helmet detection model: `'new_helmet_model.h5'`

4. Run the script:

   ```bash
   python helmetcode.py
   ```

## Prerequisites

- Python 3.x
- OpenCV
- Numpy
- imutils
- Keras

## Usage

The script captures frames from a video stream (either a file or a camera) and performs object detection using MobileNet SSD. It then classifies the presence of helmets on detected persons using a pre-trained helmet detection model.

Modify the script parameters, such as video file path or camera configuration, if needed.

```bash
python helmetcode.py
```
