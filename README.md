# Yellow Leaf Disease Detection and Autonomous Aerial Spraying Mechanism for Arecanut

This project combines AI and IoT to detect yellow leaf disease in arecanut plantations and apply pesticide precisely using an autonomous drone-mounted spraying mechanism. It leverages a ResNet-50-based classifier and an ESP32-CAM module for real-time disease detection and targeted spraying.

## 🚀 Features

- Real-time detection of yellow leaf disease using ResNet-50.
- Classification into four categories: Healthy, Yellow Leaf, Other, and No Leaf.
- Autonomous spraying using a 12V DC pump triggered by ESP32.
- Drone-compatible and modular hardware design.
- Achieved 99.35% validation accuracy on test dataset.

## 🧠 Technologies Used

- Python, OpenCV, Keras, TensorFlow
- ESP32-CAM, 12V DC sprayer pump, relay modules
- CREO for CAD modeling
- 3D printing and laser-cut components
- Drone platform for deployment

## 📂 Project Structure

```
code/           → Model training code
models/         → Trained ResNet50 model
hardware/       → Circuit diagrams, 3D CAD models
video/          → Drone operation demo
docs/           → Final project report
```

## 📦 Requirements

```bash
tensorflow==2.x
keras
opencv-python
numpy
matplotlib
```

Install using:
```bash
pip install -r requirements.txt
```

## 🛠️ How It Works

1. **Image Capture**: ESP32-CAM captures real-time images of arecanut leaves.
2. **Classification**: The image is processed by the ResNet-50 model.
3. **Spray Activation**: If yellow leaf disease is detected, a relay triggers the sprayer pump.
4. **Precision Spraying**: Pesticide is sprayed for 5 seconds using a calibrated nozzle.
5. **Loop**: The process repeats as the drone moves across the plantation.

## 📷 Demo

[📹 Watch the Drone Demo](video/drone_demo.mp4)

## 📄 Report

Detailed methodology, hardware specs, results, and CAD models can be found in [project_report.pdf](docs/project_report.pdf).

## 📘 IEEE Publication

This project has been officially published in IEEE. You can read the paper here: [IEEE Xplore - Yellow Leaf Disease Detection and Autonomous Aerial Spraying](https://ieeexplore.ieee.org/document/10895610)

## 🔒 License

MIT License

## 👨‍🔬 Authors

- Veeresha R.K.
- Shilpa M.K.
- Lathish Kumar N D
- Swaroop
- Samarth S Shetty
- Shrajan G Prasad

Presented at **IEEE ICRASET 2024**  
Patent application submitted.
