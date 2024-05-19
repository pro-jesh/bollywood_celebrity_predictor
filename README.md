# Bollywood Celebrity Predictor
A python based application which takes a picture, with a clearly visible face in it, as input and gives the closest resembling bollywood actor as an output.   
The dataset is taken from https://www.kaggle.com/datasets/sushilyadav1998/bollywood-celeb-localized-face-dataset
  

## Packeges Used:
 ![Python][python] ![scikit-learn][sklearn-image] ![Pandas][Pandas-image] ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Jupyter Notebook][ipython-image] ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
 
[python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[sklearn-image]:https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
[Pandas-image]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[ipython-image]: https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white

## Process:
     1. Load in an image (an image of yourself or a random image) 
     2. Extract the face out of the image using MTCNN
     3. Perform preprocessing so that the face image can be recognized.
     4. Load the image in the deep neural network “ResNet-50”.
     5. Extract the results

## Deployment:
Streamlit is used to build a front-end of the web application for Bollywood Celebrity Predictor.
# Pictures of the demonstration are given below
https://drive.google.com/file/d/1PMBc4Nodxpe4A3Gnp7yc3_Fr7T9_CW-b/view?usp=drive_link

https://drive.google.com/file/d/1P2DDnyv2F6Kt6oLNMnMbdDt-mWXYW2ql/view?usp=drive_link


