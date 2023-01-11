# Music_Emotion
A user’s emotion or mood can be detected by his/her facial expressions. These expressions can be derived from the live feed via the system’s camera.A lot of research is 
being conducted in the field of Computer Vision and Machine Learning (ML), where machines are trained to identify various human emotions or moods.Machine Learning 
provides various techniques through which human emotions can be detected. One such technique is to use CNN model with Keras.Human emotions have a strong relationship 
with music. In our proposed system, a mood-based music player is created which performs real time mood detection and plays songs as per detected mood. An important 
benefit of incorporating mood detection is customer satisfaction.

The proposed system can capture the user's facial expressions, and based on his facial expressions, extract facial reference points, and then classify them to obtain 
the user's specific emotions. After the emotions are classified, songs corresponding to the user's emotions are displayed to the user.Images are captured from the camera.
In this project a laptop webcam is used to capture the images.Preprocessing of the captured image is done by OpenCV-Haar Cascade classifier.We have used VGG-16 architecture.
Proposed architecture was trained using an adam optimizer at a learning rate = 0.001 s with batch size = 32 and epochs = 25. As this is a classification problem, 
categorical cross entropy loss function was used.All ofthe experiments were performed in python using Keras framework.

In this project, a modified VGG16 architecture based Convolutional Neural Network is implemented to classify human facial expressions i.e.happy, sad, surprise, anger and 
neutral. Real-time expression recognition is also performed by capturing images using webcam and processing through Haar Cascade Classifier using OpenCV.Finally a good 
recognition rate with an accuracy of 85% is obtained with epochs value 15.Used web scrapping and YouTube APIs to fetch play music from YouTube.
