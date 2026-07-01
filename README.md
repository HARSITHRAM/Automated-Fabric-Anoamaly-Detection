# AI-Based Fabric Anomaly Detection System

## Overview

The **AI-Based Fabric Anomaly Detection System** is an industrial computer vision solution developed for textile manufacturing. The system automatically inspects garments after the ironing process and before folding, ensuring that only defect-free garments proceed further in the production line.

The primary objective is to eliminate manual inspection by detecting defects in real time with high accuracy, improving product quality, reducing production losses, and increasing manufacturing efficiency.

---

# Problem Statement

In textile manufacturing, garments pass through an ironing machine where wrinkles are removed before they are folded. During this stage, defects that were previously hidden become clearly visible.

The challenge is to automatically inspect every garment while it is moving on the production line and detect any abnormalities without interrupting production.

The system should identify defects such as:

* Fabric tears
* Holes
* Stains
* Foreign colored threads
* Loose threads
* Remaining wrinkles
* Burn marks
* Color patches
* Missing or damaged stitching
* Any unknown anomalies

---

# Objectives

* Automate garment quality inspection.
* Detect visible defects in real time.
* Reduce dependency on manual inspection.
* Minimize defective products reaching customers.
* Improve production efficiency and quality control.

---

# System Workflow

```text
Wrinkled Garment
        │
        ▼
Ironing Machine
        │
        ▼
Camera Inspection Zone
        │
        ▼
Image Processing
        │
        ▼
AI-Based Defect Detection
        │
        ▼
Decision Engine
      ├── Pass
      └── Reject / Alert
```

---

# Features

* Real-time fabric inspection
* Automatic anomaly detection
* Detection of multiple defect categories
* High-speed image processing
* Industrial camera integration
* PLC-ready output for production lines
* Scalable for different garment types

---

# Types of Defects Detected

## Fabric Damage

* Tears
* Holes
* Cuts
* Burn marks

## Surface Defects

* Oil stains
* Ink stains
* Water stains
* Dirt

## Thread Defects

* Loose threads
* Foreign colored threads
* Broken stitches

## Appearance Defects

* Remaining wrinkles
* Color patches
* Print defects
* Fabric deformation

---

# Technology Stack

## Programming Language

* Python

## Computer Vision

* OpenCV

## Deep Learning

* PyTorch

## AI Models

* YOLO (Object Detection)
* Anomalib (Anomaly Detection)

## Deployment

* ONNX
* TensorRT (optional)

---

# Hardware Requirements

* Industrial RGB Camera
* Diffused LED Lighting
* Industrial PC / GPU Workstation
* Conveyor Trigger Sensor
* PLC Interface
* Mounting Frame

---

# Project Structure

```
Fabric-Anomaly-Detection/
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
│
├── training/
│
├── inference/
│
├── utils/
│
├── output/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

# Methodology

1. Capture garment images after ironing.
2. Preprocess captured images.
3. Detect garment region.
4. Run AI-based inspection.
5. Identify defects.
6. Classify garment as **Pass** or **Fail**.
7. Send output to production system.

---

# Expected Output

For every inspected garment, the system provides:

* Defect Type
* Defect Location
* Confidence Score
* Pass/Fail Status

Example:

```
Garment ID : G10235

Status : FAIL

Detected Defects

• Hole
• Foreign Red Thread

Confidence : 98.6%
```

---

# Future Improvements

* Multi-camera inspection
* 360° garment inspection
* Defect severity classification
* Automatic rejection mechanism
* Edge AI deployment using NVIDIA Jetson
* Production dashboard with analytics
* Defect trend prediction

---

# Applications

* Textile Manufacturing
* Garment Export Industries
* Apparel Quality Inspection
* Automated Production Lines
* Smart Manufacturing (Industry 4.0)

---

# Benefits

* Faster inspection
* Consistent quality
* Reduced labor costs
* Lower product rejection rates
* Increased customer satisfaction
* Real-time quality monitoring

---

# Contributors

Developed as an industry-oriented computer vision project for automated textile quality inspection.

---

# License

This project is intended for academic and industrial research purposes.
