# SmartVision - AI Traffic Violation Detection

## Project Overview

SmartVision is an AI-based traffic violation detection system that analyzes traffic video footage using computer vision and deep learning.

The system detects and tracks vehicles, monitors a virtual stop line, detects the traffic-light state, and identifies potential red-light violations. When a violation is detected, the system generates visual evidence and records the violation details in a CSV report.

## Features

- Vehicle detection using YOLO
- Vehicle tracking using ByteTrack
- Red traffic-light detection
- Virtual stop-line monitoring
- Automatic traffic violation detection
- Evidence image generation
- CSV violation report generation
- Processed output video
- Visual violation alerts

## Technologies Used

- Python
- YOLO
- ByteTrack
- OpenCV
- NumPy
- CSV
- Google Colab
- FFmpeg

## System Workflow

```text
Traffic Video
      ↓
YOLO Vehicle Detection
      ↓
ByteTrack Vehicle Tracking
      ↓
Traffic Light Detection
      ↓
Virtual Stop Line Monitoring
      ↓
Violation Detection
      ↓
Evidence Generation
      ↓
CSV Report
      ↓
Final Output Video
