# 🚗 BNU Vehicle Detection System

AI-powered gate monitoring system that automatically detects BNU vehicles using computer vision.

## 📋 Project Overview
This system detects BNU car stickers and number plates in real-time using YOLOv8 object detection model, EasyOCR for plate reading, and SQLite for database logging.

## 🎯 Features
- ✅ BNU sticker detection (YOLOv8)
- ✅ Number plate recognition (EasyOCR)
- ✅ Real-time vehicle classification (BNU / Non-BNU)
- ✅ Automated database logging with timestamps
- ✅ Web-based monitoring dashboard

## 📊 Model Performance
| Metric | Score |
|--------|-------|
| Precision | 95.4% |
| Number Plate mAP50 | 83.5% |
| Training mAP50 | 89% |
| Dataset Size | 87 images |

## 🛠️ Tech Stack
- **Model:** YOLOv8 Nano (Ultralytics)
- **OCR:** EasyOCR
- **Database:** SQLite
- **Backend:** Python + OpenCV
- **Frontend:** HTML/CSS/JavaScript
- **Training:** Google Colab (Tesla T4 GPU)
- **Annotation:** Roboflow

## 📁 Repository Structure
