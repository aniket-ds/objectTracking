# MOT Algorithm using Deep SORT and YOLOv3

![output](https://github.com/aniket-ds/objectDetection-deep_sort/assets/73283093/5eda92b5-1691-4e10-bc47-a705dc152f0d)


This repository contains an implementation of a Multiple Object Tracking (MOT) algorithm using Deep SORT (Simple Online and Realtime Tracking) in combination with YOLOv3 (You Only Look Once version 3) object detection.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Multiple Object Tracking (MOT) is an essential task in computer vision and robotics that involves tracking multiple objects over time in a video stream. This repository provides an implementation of a MOT algorithm that utilizes the Deep SORT algorithm for object tracking and YOLOv3 for object detection.

### Key Features

- Real-time object detection using YOLOv3.
- Online and robust multi-object tracking with Deep SORT.
- High accuracy and robustness in tracking objects across frames.

## Installation

To install and set up the MOT algorithm using Deep SORT and YOLOv3, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/aniket-ds/objectDetection-deep_sort.git
cd objectDetection-deep_sort
```
2. Install the required dependencies. Ensure you have Python 3.x installed.

```bash
pip install -r requirements.txt
```

3. Download the YOLOv3 pre-trained weights and configuration files from the official YOLO website (or any other reliable source) and place them in the appropriate directory.

4. Download the Deep SORT pre-trained weights and place them in the respective directory.

## Usage
To use the MOT algorithm with Deep SORT and YOLOv3, follow these steps:

1. Prepare your video or camera stream for object detection and tracking.

2. Run the MOT algorithm using the following command:

```bash
python myTracker.py 
```

3. The MOT algorithm will process the video frames, perform object detection using YOLOv3, and apply Deep SORT for tracking objects.

4. The tracked video will be saved in the specified output directory (or default directory) with bounding boxes and object IDs.

## Configuration
The MOT algorithm can be further configured by adjusting parameters and settings in the config.yml file. You can fine-tune the tracking parameters, YOLOv3 settings, and other options to suit your specific use case.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to open a pull request or create an issue in the repository.

## License
This project is licensed under the MIT License. Feel free to use and modify the code as per the terms of the license.
