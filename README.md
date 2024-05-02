# Image Processing APK (Upload or Take Photo) using React Native and Android Studio

## Midterm Exam in Mobile Development 2

This repository contains the source code for an Image Processing Android application developed using React Native and Android Studio.  It allows users to either capture a photo using the device's camera or select an image from the device's gallery. After selecting or capturing an image, users can then perform image prediction using a pre-trained model deployed on a server. The app communicates with a backend server deployed at http://192.168.1.21:5000, which employs Flask. Flask is a Python micro web framework serving the image processing model and handling prediction requests. Ensure the server is operational and reachable from the app. The server should expose an /predict endpoint for image prediction.

