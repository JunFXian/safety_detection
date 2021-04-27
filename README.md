# Construction Site Worker Safety Detection

This project is for helping the safety managers on a contruction site to check if workers wear proper safety protection gears.
The project is running in Python3 environment, and the script is running on Jyputer notebook. 

## Installation

Below is the list of libraries that the project is using:
1. Python3: https://www.python.org/downloads/
2. OpenCV: https://opencv.org/
3. Pandas: https://pandas.pydata.org/
4. PyTorch: https://pytorch.org/
5. PyTorch Lightning: https://www.pytorchlightning.ai/
6. Matplotlib: https://matplotlib.org/
7. pyqt5: https://pypi.org/project/PyQt5/
8. Jupiter Lab: https://jupyter.org/
9. Php: https://www.php.net/

## Usage

The project helps keeping the construction site environment safe for everyone on site. The project will have a simple webapp that allows user to upload construction site images and the webapp shows the output image with specfic object detected.

The system is not running on AWS SageMaker for this case. It is running on a local environment for this project. 
But it should be able to deploy to AWS SageMaker and run on the server if it is needed.

## Data Source

 * Helmet_Dataset, By Abhishek Annamraju:
   https://www.kaggle.com/abhishek4273/helmet-dataset
   Data Size: 667.72 MB
   Files: helmet_dataset: JPEGImages, train_labels.csv

NOTE:

Since the project only needs 100 images from the data source, the 100 images are packaged in the submission folder.

## History

Version 1.0

## Credits

This project is made by Jun Xian with the help of Github Contributors.
1. Johannes Schmidt. Train your own object detector with Faster-RCNN & PyTorch. https://johschmidt42.medium.com/train-your-own-object-detector-with-faster-rcnn-pytorch-8d3c759cfc70. Feb 23, 2021.
2. Padilla, Rafael and Passos, Wesley L. and Dias, Thadeu L. B. and Netto, Sergio L. and da Silva, Eduardo A. B. A Comparative Analysis of Object Detection Metrics with a Companion Open-Source Toolkit. Electronics, VOLUME 10. 2021.
3. Yinghan Xu, Faster R-CNN (object detection) implemented by Keras for custom data from Google’s Open Images Dataset V4. https://towardsdatascience.com/faster-r-cnn-object-detection-implemented-by-keras-for-custom-data-from-googles-open-images-125f62b9141a. Nov 19, 2018.
4. Udacity, Machine Learning Engineer Nanpdegree Program. April, 2021.

## License

N/A
