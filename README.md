# Face Recognition Attendance System

This project is a Python-based **Face Recognition Attendance System** that leverages computer vision to detect and recognize faces, marking attendance automatically. It also includes a liveness detection module based on blink detection to enhance security. This system is designed for use in schools, offices, or other environments where attendance management is required.

---

## Features

- Real-time face detection and recognition using **OpenCV** and **dlib**.
- Liveness detection through blink detection using facial landmarks.
- Attendance marking with automatic timestamping.
- Stores attendance data in a text file for easy access and reporting.
- User-friendly interface for setup and operation.
- Supports integration with external datasets for enhanced face recognition.

---

## Technologies Used

- **Python**
- **OpenCV** (for face detection and recognition)
- **dlib** (for advanced facial recognition techniques)
- **face_recognition** (for encoding and comparing faces)
- **NumPy** (for numerical operations)
- **scipy** (for calculating distances in blink detection)

---

## Setup Instructions

### Prerequisites
Ensure you have Python 3.x installed along with the following libraries:

- OpenCV
- dlib
- face_recognition
- NumPy
- scipy

### Clone the Repository
```bash
git clone https://github.com/naren-17/face-recognition-attendence-system.git
cd face-recognition-attendence-system
```

### Install Dependencies
Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Add Face Data
1. Collect images of the individuals whose faces need to be recognized.
2. Store these images in the `known_faces` folder (or a relevant directory based on your code).
3. Ensure that each person’s images are saved in separate subfolders, with folder names corresponding to their names.

### Run the System
Execute the main script to start the face recognition and attendance system:

```bash
python main.py
```

---

## Usage

1. The system will start capturing video from your webcam.
2. Faces detected will be matched against the database of known faces.
3. If a match is found, attendance is marked automatically with the current timestamp.
4. Attendance data will be saved in a file (e.g., `attendance.txt`).
5. The liveness detection feature will count blinks and display them on the screen for enhanced security.

---

## Project Structure

```plaintext
face-recognition-attendance-system/
├── known_faces/         # Folder containing known face images
├── attendance.txt       # Attendance output file
├── main.py              # Main script to run the system
├── requirements.txt     # Required dependencies
├── README.md            # Documentation
└── ...                  # Additional files and scripts
```

---

## Future Enhancements

- Add support for multiple cameras.
- Enhance the GUI for better user experience.
- Integrate with databases (e.g., MySQL) for attendance storage.
- Add email or SMS notifications for attendance updates.
- Improve accuracy using advanced deep learning models.
- Optimize liveness detection with additional methods (e.g., lip movement or head movement).

---

## Contribution
Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For questions or suggestions, feel free to reach out:

- **Name**: Naren C
- **Email**: [naren0749@gmail.com](mailto:naren0749@gmail.com)
- **GitHub**: [naren-17](https://github.com/naren-17)

---

Thank you for checking out this project! If you find it helpful, don’t forget to star the repository. 😊
