# AI-Powered Accident Detection System

An intelligent real-time accident detection system that leverages Computer Vision and Deep Learning to identify road accidents from live video feeds and automatically notify emergency contacts with location details.

## Overview

Road accidents often require immediate attention to reduce response time and save lives. This project uses YOLO-based object detection and OpenCV to monitor live video streams, detect potential accidents, and trigger automated alerts containing GPS location information.

## Features

- Real-time accident detection from video feeds
- Object detection using YOLO
- Video processing with OpenCV
- Automated emergency alerts using Twilio API
- GPS location sharing through Google Maps API
- Fast incident identification and notification

## Tech Stack

- Python
- OpenCV
- YOLO
- Twilio API
- Google Maps API

## Project Architecture

1. Capture live video stream
2. Process frames using OpenCV
3. Detect vehicles and accidents using YOLO
4. Verify accident occurrence
5. Fetch GPS location
6. Send automated alert messages
7. Share live location with emergency contacts

## Objectives

- Detect road accidents in real time
- Reduce emergency response delays
- Improve road safety through automation
- Provide accurate location-based alerts

## Dataset

- COCO Dataset (~25 GB, 1.5M annotated object instances)
- Additional testing performed on live video streams

## Future Enhancements

- Custom accident detection model trained on accident-specific datasets
- Higher detection accuracy using advanced deep learning models
- Cloud deployment for large-scale monitoring
- Web dashboard for incident visualization
- Integration with emergency services

## Current Status

Project under active development.
