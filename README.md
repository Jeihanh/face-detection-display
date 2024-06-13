# Face Detection Display

## Overview

This Java program detects faces in an image and displays the first identified face area using OpenCV.

## Requirements

- JDK
- OpenCV with Java bindings
- `imageE.jpg`
- `haarcascade_frontalface_alt2.xml`

## Setup

1. **Install JDK and OpenCV**.
2. **Place Files**:
   - `imageE.jpg` in project directory.
   - `haarcascade_frontalface_alt2.xml` in the specified path.

## Run

1. **Compile**:
   ```sh
   javac -cp .:path/to/opencv-<version>/build/bin FaceDetectionDisplay.java
