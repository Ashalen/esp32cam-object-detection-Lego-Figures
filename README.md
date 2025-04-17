# ESP32-CAM Object Detection: Obi-Wan Kenobi vs Batman - Ashalen Govender

This project uses an ESP32-CAM and a custom Edge Impulse model to detect two LEGO figures: **Obi-Wan Kenobi** and **Batman**.

The model was trained using Edge Impulse, with images captured using a phone and labelled in Edge Impulse. The detection runs directly on the ESP32-CAM and displays results in the Arduino IDE serial monitor — no SD card or cloud required.

## Purpose

This repo was built to showcase:

- Embedded AI on the ESP32-CAM  
- Image collection and model training using Edge Impulse  
- Real-time object recognition on-device (no SD card or external storage)

It's part of my personal portfolio and not intended as a tutorial.

## Results

| Obi-Wan Detected | Batman Detected |
|------------------|-----------------|
| ![Obi-Wan](results/2.png) | ![Batman](results/3.png) | ![Both Figures](results/4.png) |

## Folder Overview

ESP32 CAM LEGO/ ├── Model/ # Edge Impulse .eim model ├── code/ │ └── esp32_cam_detection_script/ # Arduino sketch for ESP32-CAM ├── images/ # Screenshots of detection results ├── results/ # Serial monitor output logs ├── .gitignore ├── LICENSE └── README.md


## Model

The Edge Impulse model is located in the `Model/` folder.

## 📄 Code

The Arduino sketch is located in `code/esp32_cam_detection_script.ino/`.

It uses the Edge Impulse inference SDK to run object detection directly on the ESP32-CAM. No additional storage or cloud connection is needed.


## 🧪 Notes

This project is for demo and showcase purposes only.

No wiring diagrams or build tutorials are included — just the essentials: code, model, and example results.

## 🔗 Credits

Built by **Ashalen Govender**  
BSc Robotics | Robotics and AI Enthusiast  
[LinkedIn](https://www.linkedin.com/in/ashalen-govender/)

