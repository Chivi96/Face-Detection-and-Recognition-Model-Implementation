# Face Detection and Recognition

## Setup

1. Install dependencies:
    ```bash
    pip install opencv-python dlib numpy scikit-learn
    ```

2. Download the Dlib models for shape prediction and face recognition:
    - [shape_predictor_68_face_landmarks.dat](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)
    - [dlib_face_recognition_resnet_model_v1.dat](http://dlib.net/files/dlib_face_recognition_resnet_model_v1.dat.bz2)

3. Extract the downloaded files and place them in the project directory.

4. Place your images in the folder specified in the script (e.g., `/content/drive/MyDrive/PicsArt`).

## Running the Project

1. Run the script to load images, detect faces, and recognize faces.
    ```python
    python script.py
    ```

2. The accuracy of the model will be printed, and images with detected and recognized faces will be displayed.

## Dependencies

- OpenCV
- Dlib
- Numpy
- Scikit-learn

