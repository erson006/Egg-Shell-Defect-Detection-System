# 🥚 Egg Shell Defect Detection System

<p align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

![TensorFlow Lite](https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

![Edge Impulse](https://img.shields.io/badge/Edge_Impulse-4B6BFB?style=for-the-badge)

![ESP32-CAM](https://img.shields.io/badge/ESP32--CAM-00979D?style=for-the-badge)

![Computer Vision](https://img.shields.io/badge/Computer_Vision-AI-success?style=for-the-badge)

</p>

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Core Features](#-core-features)
- [Mobile Application](#-mobile-application)
- [AI Model Performance](#-ai-model-performance)
- [System Architecture](#-system-architecture)
- [Technologies Used](#️-technologies-used)
- [Source Code Availability](#-source-code-availability)
- [Future Improvements](#-future-improvements)

An AI-powered egg shell defect detection system developed using Flutter, ESP32-CAM, TensorFlow Lite and Edge Impulse.

The application captures egg images using an ESP32-CAM module and performs on-device AI inference to classify eggs as **Cracked** or **Healthy**.

Besides AI inference, the application also provides LED brightness control, stepper motor control, image management, statistics dashboard and automation features.

> **Note:** This repository showcases the project architecture, mobile application and AI performance. The complete source code, trained models and datasets are maintained in a private repository.

---

# ✨ Core Features

## 🤖 Artificial Intelligence

- Egg shell defect classification
- TensorFlow Lite inference
- Edge Impulse Transfer Learning
- On-device prediction
- Confusion Matrix
- Precision, Recall and F1 Score evaluation

## 📱 Mobile Application

- Live ESP32-CAM stream
- Camera page
- AI prediction
- Smart gallery
- Statistics dashboard
- Settings panel

## ⚙️ Embedded Hardware

- ESP32-CAM
- Adjustable LED brightness
- 360° Stepper motor control
- Wi-Fi communication
- Automatic image capture

## 📂 Dataset Management

- Image history
- Prediction history
- Automatic storage
- Organized image gallery

---

# 📱 Mobile Application

The Flutter application manages hardware communication, image acquisition, AI inference and visualization of prediction results.

<table>

<tr>

<td align="center">
<b>🏠 Home Dashboard</b><br><br>
<img src="images/home.png" width="220">
</td>

<td align="center">
<b>📷 Camera & AI Analysis</b><br><br>
<img src="images/camera.png" width="220">
</td>

<td align="center">
<b>⚙️ Manual Hardware Control</b><br><br>
<img src="images/control.png" width="220">
</td>

</tr>

<tr>

<td align="center">
<b>🗂️ Analysis History</b><br><br>
<img src="images/history.png" width="220">
</td>

<td align="center">
<b>📊 Statistics Dashboard</b><br><br>
<img src="images/statistics.png" width="220">
</td>

<td align="center">
<b>🌐 ESP32 Settings</b><br><br>
<img src="images/settings.png" width="220">
</td>

</tr>

</table>

### ✨ Key Capabilities

- 📷 Live ESP32-CAM stream
- 🧠 Local TensorFlow Lite inference
- ⚡ Real-time crack detection
- 💡 Adjustable LED brightness
- ⚙️ Stepper motor control
- 📂 Analysis history
- 📊 Statistics dashboard
- 🌐 ESP32 connection settings

---

# 🧠 AI Model Performance

The egg shell defect detection model was trained using Edge Impulse Transfer Learning and exported as a TensorFlow Lite model for deployment inside the Flutter application.

Inference is performed completely offline on the mobile device.

<table>

<tr>

<td align="center">

<b>📊 Transfer Learning</b><br><br>

<img src="images/transfer-learning-results.png" width="420">

</td>

<td align="center">

<b>✅ Model Testing</b><br><br>

<img src="images/model-testing-results.png" width="420">

</td>

</tr>

<tr>

<td align="center">

<b>📈 Feature Explorer</b><br><br>

<img src="images/feature-explorer.png" width="420">

</td>

<td align="center">

<b>📉 Data Explorer</b><br><br>

<img src="images/data-explorer.png" width="420">

</td>

</tr>

</table>

---

## 📋 Performance Summary

| Metric | Value |
|---------|------:|
| Validation Accuracy | **97.0%** |
| Model Testing Accuracy | **90.38%** |
| Validation Precision | **0.97** |
| Validation Recall | **0.97** |
| Validation F1 Score | **0.97** |
| Test Precision | **0.91** |
| Test Recall | **0.91** |
| Test F1 Score | **0.91** |
| Deployment | **TensorFlow Lite** |

---

### 🚀 Highlights

- Transfer Learning based image classification
- TensorFlow Lite deployment
- Offline AI inference
- Crack detection in real time
- Feature visualization
- Dataset validation

---

# 🏗️ System Architecture

```mermaid
flowchart TD

A([🥚 Egg])

B[📷 ESP32-CAM]

C[📱 Flutter Application]

D[🧠 TensorFlow Lite]

E{Prediction}

F[🟢 Healthy Egg]

G[🔴 Cracked Egg]

H[💡 LED Control]

I[⚙️ Stepper Motor]

J[📷 Image Capture]

K[📂 History]

L[📊 Statistics]

M[⚙️ Settings]

A --> B

B -->|Wi-Fi| C

C --> D

D --> E

E --> F

E --> G

C --> H

C --> I

C --> J

J --> K

K --> L

C --> M
```

---

# 🛠️ Technologies Used

| Category | Technology |
|----------|------------|
| Mobile Framework | Flutter |
| Programming Language | Dart |
| AI Framework | TensorFlow Lite |
| AI Development | Edge Impulse |
| Hardware | ESP32-CAM |
| Communication | Wi-Fi |
| Computer Vision | Image Classification |
| Embedded Control | Stepper Motor & LED |

---

# 🔒 Source Code Availability

This repository presents the application's architecture, AI workflow, mobile interface and model evaluation.

The complete Flutter source code, ESP32 firmware, TensorFlow Lite model and dataset are maintained in a private repository to protect the project's intellectual property.

For research collaboration, commercial licensing or a live demonstration, feel free to contact me.

---

# 🚀 Future Improvements

- Multi-class defect detection
- Automatic dataset expansion
- Cloud synchronization
- Remote monitoring
- Explainable AI visualization
- OTA firmware updates
- Performance optimization
