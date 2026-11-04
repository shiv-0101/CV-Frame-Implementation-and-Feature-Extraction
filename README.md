# Computer Vision with Python

## 📖 About this project

This project is a practical study of computer vision using Python. It can be used to improve
an image, find important patterns, recognise objects, and track movement.

The project uses a collection of images and videos to demonstrate these ideas
step by step. Instead of only using ready-made tools, the notebooks also show
how several basic computer vision methods work and how their results can be
compared visually.

The work is organised into four Jupyter notebooks. Each notebook focuses on a
different part of computer vision and saves its results so that the output can
be reviewed later.

## 🎯 Why I made this project

I made this project to learn how computer vision works in practice.

This project helped me move from simple image operations to more advanced
tasks such as object detection and motion analysis. It also gave me practice
with preparing input data, selecting suitable methods, checking results, and
presenting the output clearly.

## 📌 Project goals

The main goals of this project are to:

- Understand how images are represented and processed by a computer.
- Learn how noise can affect an image and how it can be reduced.
- Separate useful objects or regions from their background.
- Extract features that describe the shape and appearance of an image.
- Detect faces and other objects in images and videos.
- Estimate movement between video frames.
- Compare different techniques by looking at their results.
- Build confidence using Python libraries for computer vision.

## 🔍 Topics covered

- **Task 1: Image restoration and segmentation**

  This notebook begins with image noise and restoration. It compares Gaussian
  noise and salt-and-pepper noise, then applies methods to improve the image.
  It also covers binary thresholding, Otsu thresholding, adaptive thresholding,
  morphological operations, Canny edge detection, and watershed segmentation.

- **Task 2: Feature extraction and matching**

  This notebook explores how useful information can be extracted from an
  image. It uses HOG to describe image shapes and SIFT to find keypoints and
  descriptors. These features can help compare images and identify similar
  visual patterns.

- **Task 3: Object detection**

  This notebook detects faces with a Haar cascade classifier and detects
  objects with the YOLO model. It shows the difference between a traditional
  detection method and a modern deep learning approach.

- **Task 4: Motion estimation**

  This notebook works with video frames to study movement. It uses frame
  differencing, GMM background subtraction, and Lucas-Kanade optical flow.
  It also applies YOLO to video and produces an annotated output video.

## 💡 What I learned

Through this project, I learned that there is no single computer vision method
that works best for every problem. The right method depends on the image
quality, lighting, background, amount of movement, and the result that is
needed.

I learned how thresholding can separate parts of an image, how morphological
operations can clean up a mask, and how edge detection can reveal object
boundaries. I also learned that feature descriptors provide a useful way to
compare images even when the images are not exactly the same.

The object detection and motion tasks showed me that real-world data can be
more difficult than sample images. Changes in lighting, camera movement,
occlusion, and background detail can affect the output. Viewing and comparing
the results was an important part of understanding these problems.

## 📁 Project structure

- [`data/`](./data) contains the input image, videos, and Haar cascade model.
- [`notebooks/`](./notebooks) contains the four notebooks with the experiments.
- [`outputs/`](./outputs) contains generated images, feature files, and
  annotated videos.
- [`report/`](./report) contains supporting project report files.
- [`README.md`](./README.md) contains this project guide.

## ⚙️ Getting started

1. Install Python 3 and Jupyter Notebook.
2. Install the main dependencies:

   ```bash
   pip install opencv-python numpy matplotlib scikit-image ultralytics
   ```

3. Open the notebooks in [`notebooks/`](./notebooks) using Jupyter Notebook or
   JupyterLab.
4. Run the notebooks in order, starting with `Task1.ipynb`.

The notebooks use files from `data/` and save their results in `outputs/`.
Some notebooks use pretrained models, so an internet connection may be needed
the first time they are run.

## 🛠️ Tools and libraries

- Python
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- Ultralytics YOLO

## ✅ Final note

This is a learning and experimentation project. The notebooks show the
processing steps as well as the final results, so they can be used to
understand the methods and repeat the experiments with other images or videos.
