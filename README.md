# Computer Vision

A hands-on repository for exploring computer vision through practical quizzes and mini-projects. The topics range from image processing and camera workflows to video analysis and deep learning-based vision tasks.

The repository is organized as a learning path, with each topic introducing concepts and opportunities to experiment with computer vision techniques.

## Topics Covered

- Image Annotation
- Image Enhancement
- Accessing the Camera
- Video Writing
- Image Filtering
- Image Features and Alignment
- Panorama
- High Dynamic Range (HDR)
- Object Tracking
- Face Detection
- TensorFlow Object Detection
- Pose Estimation using OpenPose

## Getting Started

### Prerequisites

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- TensorFlow, for the object detection exercises
- OpenPose, if required for the pose estimation exercise

### Installation

Clone the repository:

```bash
git clone https://github.com/aftb777/Computer-Vision.git
cd Computer-Vision
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

On macOS or Linux:

```bash
source venv/bin/activate
```

On Windows:

```powershell
venv\Scripts\activate
```

Install the packages needed for your exercises. For example:

```bash
pip install opencv-python numpy matplotlib scikit-image jupyter
```

Install TensorFlow separately if you plan to work on the TensorFlow object detection exercise:

```bash
pip install tensorflow
```

Open the notebooks with Jupyter:

```bash
jupyter notebook
```

## Learning Path

1. **Image Annotation**  
   Learn to label visual data, draw bounding boxes, and mark regions of interest in images.

2. **Image Enhancement**  
   Explore techniques such as contrast adjustment, histogram equalization, and sharpening.

3. **Accessing the Camera**  
   Use OpenCV to capture, process, and display frames from a live camera stream.

4. **Video Writing**  
   Learn to save video streams to files with different codecs and frame settings.

5. **Image Filtering**  
   Apply filters to reduce noise, smooth images, and emphasize image features.

6. **Image Features and Alignment**  
   Explore feature extraction and alignment techniques used in image matching and recognition.

7. **Panorama**  
   Learn how overlapping images can be stitched together to create a wider view.

8. **High Dynamic Range (HDR)**  
   Combine multiple exposures to capture detail in both highlights and shadows.

9. **Object Tracking**  
   Explore techniques for tracking moving objects in video.

10. **Face Detection**  
    Detect faces in images and video using computer vision methods.

11. **TensorFlow Object Detection**  
    Explore deep learning-based object detection and model inference.

12. **Pose Estimation using OpenPose**  
    Estimate human body keypoints for applications such as motion analysis and activity recognition.