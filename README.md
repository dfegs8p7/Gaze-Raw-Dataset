# Gaze-Raw-Dataset
A High-Resolution 12-bit RAW Dataset for Gaze Estimation

## Introduction

The Gaze-Raw Dataset is a novel gaze estimation dataset that captures high-resolution 12-bit RAW images directly from CMOS image sensors, eliminating the need for an Image Signal Processor (ISP). This dataset is specifically designed for deep learning-based gaze estimation, providing a high-fidelity representation of eye movement data.

Unlike traditional RGB-based datasets, Gaze-Raw retains full-bit-depth information, ensuring a more accurate estimation of gaze direction. It is intended for research in computer vision, human-computer interaction (HCI), and gaze-based assistive technologies.

## Dataset Features

Total Images: 11,189

Participants: 10

Image Format: 12-bit RAW

Resolution:

Cropped eye images: 160 × 96

Gaze Labeling: Each image is annotated with 2D gaze angles (Pitch, Yaw)

Gaze Range:

Horizontal (Yaw): ±32°

Vertical (Pitch): ±18°

## Benchmark & Performance

The Gaze-Raw dataset was tested on multiple state-of-the-art gaze estimation models. Using our proposed MAFN (Multibit Attention Fusion Network), we achieved a state-of-the-art angular error of 2.17° on our dataset.

## Comparison with Existing Datasets

| Dataset            | Participants | Targets | Range         | Sample Size | Format | Resolution      |
|--------------------|--------------|---------|---------------|-------------|--------|-----------------|
| **MPIIGaze**  | 15           | cont.   | ±20°, ±20°    | 213,659     | RGB    | 1280 × 720      |
| **Columbia**  | 56           | 21      | ±15°, ±10°    | 5,880       | RGB    | 5184 × 3456     |
| **Ut Multiview** | 50        | 160     | ±50°, ±36°    | 115,200     | RGB    | 1280 × 1024     |
| **EYEDIAP**   | 16           | cont.   | ±25°, ±20°    | Video       | Video  | VGA             |
| **GazeCapture**| 1,474        | cont.   | ±20°, ±20°    | 2,445,504   | RGB    | 640 × 480       |
| **Gaze360**   | 238          | cont.   | ±140°, ±50°   | 172,000     | RGB    | 4096 × 3382     |
| **Gaze-Raw**| 10           | cont.   | ±32°, ±18°    | 11,189      | RAW    | 1920 × 1080     |
