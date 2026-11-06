# 🍉 3D Fruit Ninja — Hand Gesture Controlled Game

A custom-built 3D Fruit Ninja game developed from scratch, featuring real-time hand tracking and gesture-based interaction through a webcam.

This project combines computer vision, gesture recognition, networking, and game development to create an interactive gaming experience without relying on traditional input devices.

## 🎮 Project Overview

3D Fruit Ninja is an independently developed game that allows players to interact with gameplay using natural hand movements in front of a webcam.

A Python-based computer vision controller tracks hand landmarks, processes gestures, and communicates with the GameMaker application through UDP networking.

The game also features a bilingual interface supporting **Persian (Farsi) and English**.

## ✨ Key Features

- **Custom 3D Game:** Developed from scratch using GameMaker.
- **Real-Time Hand Tracking:** Webcam-based hand tracking powered by MediaPipe.
- **Gesture-Based Controls:** Natural hand movements and pinch gestures.
- **Virtual Sword Interaction:** Hand movements translated into slicing interactions.
- **Bilingual Interface:** Persian (Farsi) and English language support.
- **Hand-Controlled Menus:** Interactive menu navigation.
- **Custom UI:** Tutorials, instructions, pause interface, and gameplay feedback.
- **Real-Time Communication:** UDP networking between the Python controller and GameMaker.

## 🧠 Technical Architecture

The project consists of two main components.

### 1. Hand Tracking Controller

Developed with Python, OpenCV, and MediaPipe.

Responsibilities:
- Webcam frame acquisition.
- Hand landmark detection and tracking.
- Hand movement and gesture processing.
- Sending tracking data to the game through UDP.

### 2. Game Application

Developed using GameMaker and GML.

Responsibilities:
- Receiving hand-tracking data.
- Translating hand movements into game interactions.
- Managing gameplay and slicing mechanics.
- Rendering the game environment and user interface.

### Communication Pipeline

`Webcam → Python → OpenCV / MediaPipe → Gesture Processing → UDP → GameMaker → Gameplay`

## 🛠️ Technology Stack

| Technology | Application |
|---|---|
| GameMaker / GML | Game development |
| Python | Hand tracking controller |
| MediaPipe | Hand landmark detection |
| OpenCV | Webcam capture and image processing |
| UDP | Real-time communication |

## 📸 Screenshots

Visual demonstrations of the game, interface, and hand-tracking interaction will be added here.

## 🎥 Gameplay Demonstration

Gameplay recordings and real-time hand-control demonstrations will be published here.

## 🏗️ Project Architecture

A technical architecture diagram will be added here to illustrate the interaction between the computer vision controller and the game application.

## 🔒 Source Code & Project Availability

The complete game source code is maintained in a separate private repository due to the project's proprietary nature.

This public repository serves as a portfolio showcase, presenting the project's features, technical architecture, and development work without exposing proprietary source code or assets.

---

**Developed from scratch as an independent game development project.**