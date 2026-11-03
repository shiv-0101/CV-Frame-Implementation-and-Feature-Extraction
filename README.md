# Computer Vision Project

This project contains four Jupyter notebooks that demonstrate common computer
vision techniques using Python and OpenCV.

## What is included?

- **Task 1:** Image restoration, thresholding, morphology, edge detection, and
  watershed segmentation.
- **Task 2:** HOG features and SIFT feature matching.
- **Task 3:** Face detection with Haar cascades and object detection with YOLO.
- **Task 4:** Motion estimation using frame differencing, background
  subtraction, optical flow, and YOLO video detection.

The input images, videos, and Haar cascade model are in [`data/`](./data).
Generated figures and videos are saved in [`outputs/`](./outputs).

## Running the notebooks

1. Install Python 3 and Jupyter Notebook.
2. Install the main dependencies:

   ```bash
   pip install opencv-python numpy matplotlib scikit-image ultralytics
   ```

3. Open the notebooks in [`notebooks/`](./notebooks) and run them in order.

The notebooks create the result files in the `outputs` folder.
