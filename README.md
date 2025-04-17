# ESP32-CAM Object Detection: Obi-Wan Kenobi vs Batman - Ashalen Govender

This project uses an ESP32-CAM and a custom Edge Impulse model to detect two LEGO figures: Obi-Wan Kenobi and Batman.

The model was trained using Edge Impulse, with images captured with a phone camera and labelled in Edge Impulse. The detection runs directly on the ESP32-CAM, showing results via the serial monitor in the Arduino IDE.

## Purpose

Built as part of a personal portfolio to demonstrate:
- Embedded AI using the ESP32-CAM
- Image data collection and model training with Edge Impulse
- Real-time object recognition (no SD card or external storage)

## 📸 Sample Detections

| Obi-Wan Detected | Batman Detected |
|------------------|-----------------|
| ![Obi-Wan](images/detection-screenshot-1.png) | ![Batman](images/detection-screenshot-2.png) |

## 📦 Model

The Edge Impulse model (`.eim`) is included in the `/model` folder.

## 🧪 Results

```txt
[INFO] Running inference...
Detected class: Obi-Wan Kenobi (confidence: 93.2%)
