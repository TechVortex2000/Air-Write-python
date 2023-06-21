# Virtual Pen Project

🖊️📷💻

The Virtual Pen project is a Python application that allows you to write in the air using your laptop's camera. It utilizes computer vision techniques to track the motion of a colored object, simulating the experience of writing with a pen. Additionally, it provides an eraser functionality to erase the written text. 🌬️🧽

## Features

- Capture video frames from the laptop camera.
- Track the position of a colored object (pen) to simulate writing in the air.
- Provide an eraser functionality to erase the written text.
- Display real-time video with the pen and eraser icons overlaid.
- Smooth drawing by reducing noise and applying morphological operations.
- Adjustable canvas size and window.
- Utilize the OpenCV library for computer vision tasks.
- Leverage the numpy library for efficient array operations and mathematical functions.
- Track time intervals using the time library. ⏰

## Libraries Used

📚 **numpy (imported as np)**: Provides support for multi-dimensional arrays and mathematical functions used for numerical operations.
📚 **cv2 (OpenCV)**: A popular computer vision library that offers various functions and algorithms for image and video processing. It includes capturing frames from a camera, image manipulation, and contour detection.
📚 **time**: Provides functions for time-related operations, such as measuring time intervals and delays.

## Installation

To run the Virtual Pen project, you need to have Python and the required libraries installed on your system. Follow these steps:

1. Install Python: Download and install Python from the official website - [Python.org](https://www.python.org/). Follow the instructions specific to your operating system.

2. Install numpy and OpenCV: Open a command prompt or terminal and run the following commands:

   ```shell
   pip install numpy
   pip install opencv-python
   ```

## Usage

1. Clone the repository or download the project files to your local machine.

2. Make sure your laptop camera is working properly.

3. Open a command prompt or terminal and navigate to the project directory.

4. Run the following command to start the Virtual Pen application:

   ```shell
   python virtual_pen.py
   ```

5. A new window will open displaying the video feed from your laptop camera.

6. Hold a colored object (pen) in front of the camera and move it in the air to simulate writing.

7. To erase the written text, hold the eraser (another colored object) in front of the camera and move it over the text.

8. Adjust the canvas size and window as needed using the trackbars provided.

9. Press the 'q' key to quit the application.

## Contributing

Contributions to the Virtual Pen project are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request on the project's GitHub repository.
```

Feel free to use this code as a starting point and modify it as needed for your project.