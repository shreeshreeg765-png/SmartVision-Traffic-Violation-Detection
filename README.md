# SmartVision - AI Traffic Violation Detection

## Project Overview

SmartVision is an AI-based traffic violation detection system that analyzes traffic video footage using computer vision and deep learning.

The system detects vehicles, tracks them using ByteTrack, monitors a virtual stop line, and identifies potential red-light violations.

## Features

- Vehicle detection using YOLO
- Vehicle tracking using ByteTrack
- Red traffic-light detection
- Virtual stop-line monitoring
- Automatic traffic violation detection
- Evidence image generation
- CSV violation report
- Processed output video

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

## Results

The system detected:

- Total Violations: 10
- Evidence Images: 10
- Final Video Size: 5.67 MB

## Project Outputs

The system generates:

- Final processed traffic video
- Violation evidence images
- CSV violation report

## Future Scope

- License plate recognition
- Lane violation detection
- Illegal U-turn detection
- Speed violation detection
- Real-time CCTV monitoring

## Platform

Developed using Google Colab with GPU-accelerated AI processing.
