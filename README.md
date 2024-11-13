# Progect

This project, **Progect**, is a real-time object detection web application designed for dynamic video streaming, object detection, and user interactivity. It allows users to stream live video, detect objects in real-time, and download detection logs with customizable detection settings.
![Uploading obj.jpg…]()



## Tech Stack

The following technologies are used in this project:

- **HTML**: Structures the layout for video display, object detection details, and user controls.
- **JavaScript**: Adds interactivity, enabling real-time video updates, detection settings adjustments, and log downloads.
- **Python**: Manages backend operations, video processing, and object detection using image processing libraries.
- **Flask**: Serves as the backend framework, handling HTTP requests and data flow.
- **Flask-SocketIO**: Enables real-time, bidirectional communication between frontend and backend for smooth video feed updates.
- **OpenCV**: Used in Python for real-time video frame capture, manipulation, and transformation.
- **YOLO (You Only Look Once)**: Detects objects in real-time on video frames, drawing bounding boxes and labels.
- **Pandas**: Organizes detection data into an Excel format for creating downloadable logs with metadata.
- **Socket.IO**: Ensures seamless data flow between server and client for live video stream updates.

## Features

1. **Live Video Streaming**: Stream live video directly within the web browser.
2. **Real-Time Object Detection**: Apply object detection on live video feeds with bounding boxes.
3. **Detection Settings**: Adjust detection parameters, including threshold and frequency.
4. **Downloadable Logs**: Export detection logs in JSON format, capturing details like object type, confidence level, and timestamp.
5. **Dashboard**: View current and historical detections, logs, and statistical insights.
6. **Differentiated Object Detection**: Detect different object types—**persons** and **vehicles**—with unique bounding box colors for better visual distinction.

## Future Enhancements

1. **Model Customization**: Allow users to train and deploy custom object detection models.
2. **Multi-Camera Support**: Stream and detect objects from multiple video sources simultaneously.
3. **Mobile App Integration**: Extend detection functionality to mobile platforms.
4. **Automated Alerts**: Set detection triggers to notify users in real-time for specific object detections.
5. **Advanced Analytics**: Provide insights based on detection history, heatmaps, and trends analysis.

## Potential Use Cases

Upon completion, **Progect** will be valuable across various domains:

1. **Security & Surveillance**: Automatically identify suspicious activities or unauthorized access.
2. **Retail Analytics**: Track customer behavior to optimize store layout and marketing efforts.
3. **Smart City Applications**: Monitor and manage traffic conditions in real-time.
4. **Healthcare & Assisted Living**: Observe patient movements and notify caregivers for enhanced care.
5. **Agriculture**: Monitor crop and livestock conditions using drone-based detection systems.
6. **Education & Research**: A practical tool for students and researchers exploring object detection.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/progect.git
Navigate to the project directory:

cd progect
## Install the required dependencies:

pip install -r requirements.txt
Start the application:

python app.py
Open your browser and go to http://127.0.0.1:5000 to view the application.

## Contributing
Contributions are welcome! Please follow these steps:


## Fork the repository.
Create a new branch for your feature:

git checkout -b feature-name
Commit your changes:


git commit -m "Add new feature"

## Push your branch:

git push origin feature-name
Submit a pull request for review.
Thank you for exploring Progect! We look forward to seeing how it inspires new use cases and advancements in real-time object detection.
