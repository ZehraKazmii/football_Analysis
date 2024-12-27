# Football Analysis

<P>
Here’s an alternative version of the description, emphasizing clarity and precision:

The objective of this project is to detect and track players, referees, and footballs in video footage using YOLO, a state-of-the-art AI object detection model. The project involves training YOLO to enhance its accuracy and performance. Players will be assigned to teams by analyzing the colors of their t-shirts, achieved through K-means clustering for pixel segmentation.

With this data, we will calculate the ball possession percentage for each team during a match. To measure player movements accurately, we will use optical flow to analyze camera motion between frames. Additionally, perspective transformation will be applied to account for depth and perspective in the scene, enabling measurements in meters instead of pixels.

By combining these techniques, we will compute each player’s speed, distance covered, and overall performance metrics. This project addresses real-world challenges, integrating advanced concepts, and is designed to be approachable for beginners while offering depth for experienced machine learning practitioners.</P>


## Requirements

To run this project, ensure you have the following dependencies installed:

- **Python 3.x**: Required to execute the scripts.
- **Ultralytics**: For YOLO-based object detection and tracking.
- **Supervision**: To handle video processing and annotation tasks.
- **OpenCV**: For computer vision operations, including image and video processing.
- **NumPy**: For numerical computations and array manipulations.
- **Matplotlib**: For visualizing data and generating plots.
- **Pandas**: To manage and analyze structured data.

You can install these dependencies using the following command

![fooball](https://github.com/user-attachments/assets/cb87d408-a066-433b-84df-26860f70cddd)

### Sample Video

https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view
