# Attendance_system_with_HMB

# Face Recognition System

Face Recognition System is a graphical user interface (GUI) application developed using Tkinter in Python. The application offers various functionalities related to face recognition, student management, attendance tracking, and data training.

## Features

- **Student Management:**
  - View and manage student information.

- **Face Recognition:**
  - Detect faces using a trained model.

- **Attendance Tracking:**
  - Track and manage attendance based on face recognition.

- **Data Training:**
  - Train the face recognition model with new data.

## Prerequisites

- Python 3.x
- Tkinter library
- PIL (Python Imaging Library)
- OpenCV
- Other dependencies as mentioned in the code

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Face-Recognition-System.git
    cd Face-Recognition-System
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    python main.py
    ```

## Usage

1. Launch the application by running `main.py`.
2. Use the buttons on the GUI to access different features:
   - **Student Panel:** Manage student information.
   - **Face Recognition:** Detect faces using the trained model.
   - **Attendance Panel:** Track and manage attendance.
   - **Data Training:** Train the face recognition model.
   - **Images:** Open the folder containing images.
   - **Exit:** Close the application.

## File Structure

- **Images_GUI:** Contains images used in the GUI.
- **train.py:** Module for training the face recognition model.
- **student.py:** Module for managing student information.
- **face_recognition.py:** Module for face detection and recognition.
- **attendance.py:** Module for attendance tracking.
- **main.py:** Main script for launching the GUI.

## Contributing

Contributions are welcome! Please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
