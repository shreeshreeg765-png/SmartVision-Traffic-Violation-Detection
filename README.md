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
Results

The system detected:

Total Violations: 11
Evidence Images: 11
Final Video Size: 5.67 MB
Project Outputs

The system generates:

Final processed traffic video
Violation evidence images
CSV violation report
Project Files
File	Description
Ai_Based_Traffic_Violation_Detection (2).ipynb	Complete project notebook
SmartVision_Traffic_Violation_Final.mp4	Final processed output video
violation_report (1).csv	Violation detection report
violation_*.jpg	Evidence images of detected violations
Future Scope
License plate recognition
Lane violation detection
Illegal U-turn detection
Speed violation detection
Real-time CCTV monitoring
Automated traffic monitoring dashboard
Platform

Developed using Google Colab with GPU-accelerated AI processing.

Project Summary

SmartVision demonstrates how computer vision, object detection, and object tracking can be combined to automate traffic violation monitoring and generate digital evidence for detected violations.
