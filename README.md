# Corn and Weed Detection

This repository contains a Jupyter Notebook (`CORN.ipynb`) that demonstrates an object detection model for identifying corn and weeds in images. The model leverages the Roboflow API for inference.

## Features

* **Object Detection:** Detects and classifies "maiz" (corn) and potentially "weed" objects in images.
* **Roboflow API Integration:** Utilizes `inference-sdk` to interact with a Roboflow model.
* **Bounding Box Visualization:** Draws bounding boxes and labels on the detected objects using `matplotlib` and `OpenCV`.

## Getting Started

### Prerequisites

To run this notebook, you'll need the following Python libraries:

* `inference-sdk`
* `matplotlib`
* `pillow`
* `opencv-python`
* `numpy`
* `requests`
* `dataclasses-json`
* `supervision`
* `aiohttp`
* `backoff`
* `aioresponses`
* `py-cpuinfo`

You can install these using pip:

```bash
pip install inference-sdk matplotlib pillow opencv-python numpy requests dataclasses-json supervision aiohttp backoff aioresponses py-cpuinfo
