
# Drowsiness Detection System

This project involves creating a drowsiness detection system using computer vision and machine learning techniques. The system is designed to alert drivers when signs of drowsiness are detected, enhancing road safety.

## Features

- **Real-Time Monitoring**: Continuously monitors the driver's face for signs of drowsiness.
- **Alert System**: Triggers an alert when drowsiness is detected.
- **Machine Learning**: Utilizes pre-trained models for face and eye detection.
- **User-Friendly Interface**: Simple and intuitive user interface.

## Requirements

- Python 3.x
- OpenCV
- Dlib
- Scipy
- Imutils

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/drowsiness-detection.git
   cd drowsiness-detection
   ```

2. **Download Pre-trained Models**:
   - Download the shape predictor and face detector models from [dlib's model zoo](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place them in the project directory.

## Usage

1. **Run the Detection Script**:
   ```sh
   python detect_drowsiness.py
   ```

2. **Interface**:
   - The script will open your webcam and start monitoring for drowsiness.
   - An alert will be triggered if drowsiness is detected.

## Contributing

Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

