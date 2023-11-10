# Face_Recognition_Attendance

![image](https://github.com/cosmicishan/Face_Recognition_Attendance/assets/37193732/57cdb05a-fe60-44a8-8df9-12cead19c378)


Welcome to the Face Recognition Project repository! This project utilizes the face recognition library to recognize faces in real-time using a webcam. The facial recognition process involves capturing facial encodings from a set of images, storing them in a pickle file, and then comparing the encoding of a live webcam feed with the stored encodings to identify the recognized person.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Python (>=3.6)
- face_recognition library (`pip install face_recognition`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/cosmicishan/Face_Recognition_Attendance.git
   cd Face_Recognition_Attendance
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Populate the `data/images` directory with images of individuals you want to recognize.

2. Run the following script to encode the faces and store them in a pickle file:

   ```bash
   python encode_faces.py
   ```

3. Launch the face recognition system:

   ```bash
   python main.py
   ```

   The application will open a webcam feed, and as it recognizes faces, it will display the person's information in the user interface.

## User Interface

The UI consists of an empty field that dynamically populates with information about the recognized person. The system compares the facial encoding of the person in the webcam feed with the stored encodings, selecting the individual with the lowest distance as the recognized person.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## Reference

This project is referenced from https://www.youtube.com/watch?v=iBomaK2ARyI&t=4912s

## Acknowledgments

- The face recognition library: [https://github.com/ageitgey/face_recognition](https://github.com/ageitgey/face_recognition)


