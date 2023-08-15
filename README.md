# Real-time-facial-expression-recognition

#Project setup: Python version: 3.6

Install IDE-Pycharm 

Install following libraries:

1.cv2 command: pip install opencv
2.numpy command: pip install numpy
3.dlib command: pip install dlib
4.sklearn command: pip install sklearn
5.seaborn command: pip install seaborn
6.pandas command: pip install pandasRecognition
7.matplotlib command: pip install matplotlib

dataset=This folder contains sorted set of emotions namely [anger, contempt, disgust, fear, happiness, neutral, sadness, surprise], obtained after executing 
load_dataset.py models=This folder contains list of trained models 
confusion_matrix and Accuracy=This folder contains plot of confusion matrices obtained for various classifiers and Accuracy for the same 
plot_confusion_matrix.py=This program is used to plot the confusion matrices of the following dataset 
train.py=This program is used to train different models on the dataset and save the models along with the confusion matrices 
detect_emotions.py=This program predicts the class of a static image or predicts the emotion class for a video stream
