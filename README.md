# Person Counting Script with OpenCV

This repository contains a Python script to count the number of people in a video using OpenCV. The script processes a video file and detects people's movement across predefined lines, counting the number of people going up and down.

## Requirements

To run the person counting script, you'll need the following dependencies:

- Python 3.x
- OpenCV (cv2) library for image processing

## How to Use

1. Clone this repository to your local machine:
```https://github.com/nikhilkoche/Person-counting.git
```
2. Navigate to the cloned repository:
```
cd person-counting-opencv
```

3. Place your video file (in .mp4 format) in the repository directory.

4. Open the `person_counter.py` script and modify the `video_path` variable to point to your video file:

```python
python person_counter.py
```

4. Place your video file in the Test Files directory.

5. Open the `person_counter.py` script and modify the `video_path` variable to point to your video file:




## Run the script:
```
python person_counter.py
```

The script will process the video and display the output in the terminal. It will count the number of people going up and down, along with the timestamp of each crossing event.

Adjusting Line Positions
The script will automatically adjust the positions of the counting lines based on the video's resolution. It will process the video and display the output in the terminal. The script will count the number of people going up and down, along with the timestamp of each crossing event.

# Limitations
Please note that this person counting script is a simple example and may not be suitable for all scenarios. Factors such as lighting conditions, video quality, and crowd density can affect the accuracy of the counting. More advanced computer vision techniques and machine learning models can be used for more robust people counting solutions.
