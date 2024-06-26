
---

# Pose Estimation and Exercise Counter

This repository contains Python scripts using OpenCV and Mediapipe for pose estimation. The primary focus is on counting exercises, specifically dumbbell curls in the provided example.

## Dependencies

- Python 3.x
- OpenCV
- Mediapipe



https://github.com/Aditya-tec/Pose-Estimation-and-Exercise-Counter/assets/75620159/07a91f20-3f31-461c-8761-c472b8b8db6f



You can install the required packages using the following command:

```bash
pip install opencv-python mediapipe
```

## Usage

### 1. Dumbbell Curl Counter

To count dumbbell curls from a video, run the `trainer.py` script. Update the video file path in the script accordingly:

```bash
python trainer.py
```

The script displays the video with a graphical overlay showing the curl count and the correctness of the exercise form.

### 2. Pose Estimation Demo

To run a basic pose estimation demo, execute the `posing.py` script. You can adjust the video file path in the script:

```bash
python posing.py
```

This script uses Mediapipe to estimate key landmarks and angles of body poses.

## Files

- `curls_counter.py`: Counts dumbbell curls in a given video.
- `PoseModule.py`: Module containing a PoseDetector class for pose estimation.
- `pose_demo.py`: Demonstrates basic pose estimation using the PoseDetector class.

## Credits

The pose estimation functionality is based on the [Mediapipe](https://mediapipe.dev/) library.

