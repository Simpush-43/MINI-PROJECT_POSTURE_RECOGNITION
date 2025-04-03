Posture Recognition using FastAPI & MediaPipe
📌 Overview
This is a rule-based posture recognition system that detects human postures (e.g., Standing, Sitting, Slouching, Lying Down) from images. It uses FastAPI for the backend and MediaPipe Pose for skeletal detection. Users can upload an image through a simple web interface, and the system will analyze the posture and return the result.

🚀 Features
✔ Upload images for posture detection
✔ Detects postures using a rule-based system
✔ Uses MediaPipe for skeleton landmark detection
✔ FastAPI-based backend for efficient processing
✔ Simple web interface for easy use

🔧 Technologies Used
FastAPI (Python framework for API development)

MediaPipe (Pose estimation)

OpenCV (Image processing)

NumPy (Mathematical calculations);
How to Use the Posture Recognition System
1️⃣ Upload an Image

Click on the “Upload Image” button.

Select an image containing a person’s full body.

2️⃣ Analyze Posture

After uploading, click “Analyze” to start detection.

The system will process the image and detect your posture.

3️⃣ View Results

The detected posture (Standing, Sitting, Slouching, etc.) will be displayed.

The image with detected landmarks will be shown on the screen.

4️⃣ Try Again

You can upload another image to analyze a new posture.

📌 Note: Ensure the image is clear and contains a visible full-body posture for accurate results.
📸 Sample Output
Upload an image, and the system will classify the posture.

The processed image with pose landmarks will be saved in the static/uploads folder.

🎯 Future Enhancements
Extend to real-time webcam detection

Improve accuracy with ML-based models

Add a mobile-friendly interface

📩 Contributions & Feedback
This project is part of a college mini-project. Contributions, feedback, and suggestions are welcome!

📌 Author: [Your Name]
📌 License: MIT
