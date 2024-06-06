# Car-License-Plate-Detection
Trying to detect and fetch the license plate of cars from live feed.

We have taken up a kaggle challenge for fetching the dataset and approach the problem statement.
https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

Note:
yolo_application.py is only the deployment using *Streamlit* and is NOT the whole code
The code for EDA and model development can be found in the colab (.ipynb) notebook attached or you can check my profile on kaggle
https://www.kaggle.com/code/siddharth4567/car-license-plate-detection
Please vote me up on kaggle if you find this helpful😁

demo.mp4 has the sample video on which detection is done. You can use cv2.VideoCapture(0) in place of the demo path file to access live data feed from a camera module. 0 being the camera of laptop and 1,2,3.... for the other cameras attached.
