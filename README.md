# Video Analytics: Face Detection using OpenCV

## Project Overview

This project demonstrates how to perform **face detection** on a video using OpenCV in Java. The code processes each frame of a video, detects faces using a **Haar Cascade Classifier**, and saves a new video with rectangles drawn around the detected faces.

### Features:
- **Face Detection**: Detects faces in each frame of the video.
- **Video Processing**: Reads and processes video frames.
- **Video Output**: Writes the processed video with face detection to an output file.

---

## Prerequisites

Before running the code, make sure the following tools and libraries are installed:

### 1. **Java Development Kit (JDK)**

Ensure that you have **Java JDK 8 or higher** installed. You can download the latest version from [Oracle's official JDK website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### 2. **OpenCV for Java**

You need to download and set up **OpenCV** for Java. OpenCV is a powerful library used for computer vision tasks, including face detection.

- Download OpenCV from [OpenCV Releases](https://opencv.org/releases/).
- After downloading, extract the contents and set up the OpenCV JAR and native library files.

### 3. **Haar Cascade Classifier for Face Detection**

You also need the Haar Cascade XML file for face detection, such as `haarcascade_frontalface_alt2.xml`, which is provided by OpenCV.

- You can find this file in the OpenCV repository, or download it from [this link](https://github.com/opencv/opencv/tree/master/data/haarcascades).

---

## Setup Instructions

### 1. **Install OpenCV in Java**

#### Option 1: Using Maven (Recommended)

Add the following dependency to your `pom.xml` if you are using Maven:

```xml
<dependency>
    <groupId>org.opencv</groupId>
    <artifactId>opencv</artifactId>
    <version>4.5.2</version> <!-- Replace with the latest version -->
</dependency>
