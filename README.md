# Requirements:

* Python version 3 or above (with pip, matplotlib, numpy, seaborn)
* PyTorch
* OpenCV Library for python package
* Recommended CUDA with CUDNN (For Nvidia GPU Processing)
* Yolo Version 5 Repository with yolov5s.pt model (required files are  included in this repository itself) 

# To Run (Tested on Ubuntu):

1. Clone this repository
2. Get a New Terminal from the current location
3. Type "python3 lane.py & python3 yolov5/detect.py --source ./lines.avi --view-img"
4. You can include any video as your wish by modifying the lane.py file. (here video.m4v is the selected video)


## Screenshots:

<details>
  <summary>Click to view screenshots</summary>

  ![Screenshot 1](results/ss1.png)
  ![Screenshot 2](results/ss2.png)
  ![Screenshot 3](results/ss3.png)

</details>

# Reference:
https://github.com/ultralytics/yolov5
