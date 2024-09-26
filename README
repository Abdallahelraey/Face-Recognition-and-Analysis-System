# Face Recognition and Analysis System

This project provides a comprehensive real-time face recognition and facial analysis system using Python, OpenCV, Dlib, DeepFace, and the `face_recognition` library. The system detects faces, recognizes known individuals, and analyzes various facial attributes such as age, gender, emotions, and facial landmarks.

## Features
- **Face Detection**: Detects faces in real-time using Dlib and `face_recognition`.
- **Face Recognition**: Identifies known faces by comparing them with pre-encoded face data.
- **Facial Attribute Detection**: Extracts attributes such as age, gender, emotion, and race using DeepFace.
- **Facial Landmark Detection**: Detects 68 facial landmarks using Dlib's shape predictor.
- **Real-time Video Feed**: Captures live video feed from a webcam and processes frames to display recognition and analysis results.
- **Batch Image Processing**: Processes images to detect, recognize, and analyze faces in static image files.

## Technologies
- **OpenCV**: Used for capturing video feed and image manipulation.
- **Dlib**: Used for detecting faces and predicting facial landmarks.
- **DeepFace**: Used for analyzing facial attributes such as age, gender, emotion, and race.
- **Face Recognition Library**: Used for encoding, comparing, and recognizing faces.
  
## Prerequisites
To run the project, you will need to install the following libraries:

```bash
pip install opencv-python dlib face_recognition deepface
```

Ensure you have the `shape_predictor_68_face_landmarks.dat` file, which can be downloaded from [Dlib's model page](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2).

## How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/facerecognition-system.git
   cd facerecognition-system
   ```

2. **Load known faces**: 
   Place images of known individuals into the `./images/individuals` directory. The system will automatically encode and save their face data for recognition.

3. **Run the real-time face recognition and analysis system**:
   ```bash
   python main.py
   ```
   Press `q` to quit the real-time video feed.

4. **Run the batch image face recognition and analysis**:
   To process static images:
   ```bash
   python batch_recognition.py
   ```

## File Structure
- `main.py`: Entry point for running the real-time face recognition system using live video feed.
- `batch_recognition.py`: Script for running face recognition and analysis on static images.
- `FaceRecognitionSystem.py`: Core class that handles real-time face detection, recognition, and facial attribute analysis.
- `FaceRecognitionAndAnalysis.py`: Core class that handles face recognition and analysis for static images.

## Customization
You can modify the paths for images, tune the facial analysis settings in the `DeepFace.analyze()` method, or extend the system to include additional features like face tracking.

## Example Usage

### Real-Time Video Feed
The system will:
1. Detect and recognize faces from the live camera feed.
2. Display information about each face, such as name, age, gender, and emotions.
3. Annotate the video feed with detected facial landmarks.

#### Processed Abdallah_Mohamed.jpeg: {'age': 23, 'gender': {'Woman': 0.00031815122838452226, 'Man': 99.99967813491821}, 'dominant_emotion': 'happy', 'dominant_race': 'middle eastern'}


## Contributing
If you wish to contribute to this project, please submit a pull request or open an issue.

## License
This project is licensed under the Apache License.

