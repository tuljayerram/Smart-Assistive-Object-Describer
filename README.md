# Smart Assistive Object Describer for the Visually Impaired

An AI-powered assistive system that helps visually impaired individuals identify objects in their surroundings using real-time computer vision and audio feedback. The system captures live video through a camera, detects objects using a YOLOv8 model, and announces them via text-to-speech, enabling safer and more independent navigation.

---

## 📌 Problem Statement

Visually impaired individuals face daily challenges in recognizing and identifying objects around them, which affects their independence and safety. Traditional aids such as white canes or guide dogs mainly assist with obstacle detection but do not provide information about the *identity* of objects. This project bridges that gap by converting visual information into meaningful audio descriptions using AI.

---

## 🎯 Objective

To design a **portable, affordable, and user-friendly assistive device** that:

* Detects common objects in real time
* Identifies their position (left / right / ahead)
* Provides clear audio feedback to the user

---

## 🧠 System Overview

The system works in a continuous loop:

1. Capture real-time video using a camera
2. Preprocess frames for better accuracy
3. Detect and classify objects using YOLOv8
4. Determine object direction (left/right/ahead)
5. Convert detected object labels into speech
6. Announce results through earphones or speaker

---

## 🛠️ Tech Stack

### Hardware

* Raspberry Pi Zero 2W
* USB Webcam
* Bluetooth Earphones / Speaker
* Power Bank

### Software

* Python 3.9+
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* TensorFlow Lite (runtime)
* eSpeak (Text-to-Speech)

---

## 📊 Results

* Real-time object detection at 5–10 FPS on Raspberry Pi Zero 2W
* Direction-based announcements (left / right / ahead)
* Stable detection for common indoor and outdoor objects

---

## 🌟 Key Features

* Real-time AI-based object detection
* Direction-aware audio feedback
* Lightweight and portable design
* Low-cost assistive solution
* Can be extended to wearable smart glasses

---

## 🚀 Future Enhancements

* Voice command interaction
* OCR for text and currency recognition
* GPS-based outdoor navigation
* Scene-level description
* Mobile app integration
* Improved energy efficiency

---

## 📚 Learnings

* Implemented real-time object detection on resource-constrained hardware
* Optimized AI inference for embedded systems
* Integrated computer vision with speech synthesis
* Designed assistive technology with social impact

---

## 👩‍💻 Author

**Tulja Yerram**
B.E –  Major in Electronics and Communication Engineering
  Minor in Artificial Intelligence and Machine Learning
Interests: Embedded Systems, IoT, AI, Computer Vision, Robotics

---

⭐ If you find this project useful or inspiring, feel free to star the repository!

