# Live Mouse Control Using Hand Gestures

Revolutionizing Human-Computer Interaction with Hand Tracking

## Overview

This project demonstrates a gesture-based mouse control system using real-time hand tracking and gesture recognition. It replaces traditional input devices with touchless hand gestures, enabling mouse actions like movement, clicks, and screenshots. Designed for accessibility and innovation, the system employs Python libraries such as OpenCV, MediaPipe, and PyAutoGUI for robust performance in diverse conditions.

## Features

- **Real-Time Gesture Recognition**: Recognizes and maps hand gestures to mouse actions.
- **Mouse Actions**: Includes left click, right click, double click, and screenshot capture.
- **Robust Performance**: Tested under varying lighting conditions with an average latency of ~50ms.
- **Accessibility**: Enhances interaction for individuals with physical disabilities.

## Technologies Used

- **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)**: For detecting and tracking 21 hand landmarks.
- **[OpenCV](https://opencv.org/)**: For capturing and processing video feed.
- **[PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)**: For automating mouse movements and actions.

## System Design

1. **Gesture Recognition Functions**:
   - Detects gestures like mouse movement and clicks.
   - Utilizes angles and distances between hand landmarks.

2. **MediaPipe Hand Module**:
   - Detects and tracks hand landmarks in real-time.

3. **Mouse Control Actions**:
   - Maps recognized gestures to corresponding mouse actions.

4. **Main Driver Script**:
   - Captures video feed, processes frames, detects gestures, and executes actions.

## Results

- **Accuracy**: 93% across all gestures.
- **Latency**: ~50ms per gesture.
- **User Feedback**: Intuitive and consistent gesture recognition.

## Future Enhancements

- AR/VR integration for immersive environments.
- Multimodal interaction combining voice and gestures.
- Support for multi-hand gestures for dynamic controls.
- Expanded gesture vocabulary for actions like scrolling and zooming.
