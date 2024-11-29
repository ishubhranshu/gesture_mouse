# Hand Gesture Recognition System

![Gesture UI Mapping](images/gesture_ui_mapping.png)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Gestures and Actions](#gestures-and-actions)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Overview

The **Hand Gesture Recognition System** is a real-time application that utilizes your webcam to detect hand gestures and perform corresponding UI actions on your computer. By leveraging **MediaPipe** for hand tracking, **TensorFlow** for gesture classification, and **PyAutoGUI** for automating UI interactions, this system offers an intuitive, hands-free interface for seamless computer control.

## Features

- **Real-Time Gesture Recognition**: Detects and interprets hand gestures instantly using your webcam.
- **Smooth Cursor Movement**: Moves the mouse cursor fluidly based on hand movements, ensuring precise control.
- **Automated UI Actions**: Executes actions like clicking, scrolling, and opening Task View with specific gestures.
- **Smooth Scrolling**: Implements continuous and responsive scrolling actions for enhanced navigation.
- **Cross-Platform Support**: Compatible with Windows, macOS, and Linux (with appropriate key combinations).

## Gestures and Actions

![Gesture UI Mapping](images/gesture_ui_mapping.png)

| Gesture | UI Action |
|---------|-----------|
| **Gesture 0** | Open Task View (`Windows + Tab`) |
| **Gesture 1** | Perform Mouse Click |
| **Gesture 2** | Move Mouse Cursor |
| **Gesture 3** | Scroll Up |
| **Gesture 4** | Scroll Down |

*Refer to the image above for a visual representation of each gesture and its corresponding UI action.*

## Installation

### Prerequisites

- **Python 3.7 or higher** installed on your system.

### Clone the Repository

```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
