# COVID-19 Precaution: Face Mask Detection
## Description
During the pandemic, facemask wearing is one of the most important precaution measures.[^1]
## Description
A face mask detector through ConvNet training was developed and tested with images and further employed in viedeo streams.
1. Data augmentation was conducted to prevent overfitting
1. Implemented deep learning algorithms (ConvNet) to devolop a face mask classifier in Python.
3. Visualized training and validation loss and accuracy using Matplotlib.
4. Static image test: trained and validated model was tested with static images.
5. Video test: used OpenCV pretrained human face classifier model[^2] to detect human faces on the video streams([demo](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Video)) and the face mask detection model was deployed for mask detection on human faces.
## TechStacks
Python, TensorFlow, Keras, Numpy, OpenCV
## Datasets
1. [Training datasets](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Train): 600
+ 300 human faces wearing masks 
+ 300 human faces without masks
2. [Test datasets](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Test): 100 
+ 50 human faces wearing masks 
+ 50 human faces without masks
3. [Cross-validation datasets](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Cross%20validation): 306
+ 153 human faces wearing masks 
+ 153 human faces without masks
## Results
1. Training and validation loss: 
+ ![alt text](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/blob/main/Results/Loss.png)
2. Traing and validation accuracy:
+ ![alt text](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/blob/main/Results/Accuracy.png)
3. The trained model was successfully applied to detect face masks in video stream.
+ Demo_original: 
- ![alt text](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/blob/main/Video/original.gif)[Original video](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Video) 

+ Demo_face mask detection: 
- ![alt text](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/blob/main/Video/demo_detection.gif)[Detection video](https://github.com/phoebe20200523/COVID-19-Precaution-with-face-mask-detection/tree/main/Video)
[^1]: [Advice for the public: Coronavirus disease (COVID-19).](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public).
[^2]: [OpenCV pretrained human face classifier model.](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)


