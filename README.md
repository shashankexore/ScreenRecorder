# Screen Recorder

This project captures the screen and records it into a video file using `pyautogui` and `opencv` (cv2). The recording is done at a resolution of 1920x1080 and a frame rate of 60 FPS. You can press 'q' to stop the recording.

## About the Project

This script is designed to record the screen in real time and save it as a video file (AVI format). It utilizes the `pyautogui` library to capture screenshots and `cv2` (OpenCV) to process and write the video. It's useful for creating tutorials, recording gameplay, or other screen capture tasks.

## Getting Started

### Prerequisites

Before running the script, you need to install the following dependencies:

- `pyautogui`
- `opencv-python`
- `numpy`

To install the required libraries, run the following command:

```bash
pip install pyautogui opencv-python numpy
```

### Running the Script

1. Download or clone the repository.
2. Make sure the required libraries are installed.
3. Run the script using Python:

```bash
python screen_record.py
```

The screen recording will begin immediately, and the output will be saved as `Recording.avi` in the same directory as the script. To stop the recording, press the 'q' key.

### Output

- The video will be saved as `Recording.avi` in the working directory.
- The script captures the screen at a resolution of 1920x1080 and a frame rate of 60 FPS.

## Usage

You can customize the following variables to suit your needs:
- `resolution`: Change the screen resolution for capturing.
- `fps`: Set the frame rate for the recording.
- `filename`: Specify the output file name.

## Contributing

Feel free to fork the repository, submit issues, or contribute improvements.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a pull request.

## Credits

Made by Shashank Singh.
