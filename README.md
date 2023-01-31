# CelebrityFaceRecognition

The code consists of 3 .ipynb files:
Data_Wrangling.ipynb
Classification.ipynb
Face_Detection.ipynb

Data_Wrangling.ipynb loads images of Brad Pitt and others from lists of videos and the PubFig dataset

Classification creates an instance of the pretrained VGG model, transforms the images grabbed by Data_Wrangling.ipynb, and trains a 4-layer neural network with logisitic regression fully connected layer. The weights of the linear network are saved locally to be loaded in Face_Detection.ipynb

Face_Detection.ipynb uses our pretrained VGG16 and linear networks to read each frame of an input video, assign each face in the frame with a confidence of being Brad, and draws a bounding box around the face with highest confidence, if appropriate.


Dataset:
Our training and testing images are located in the below Google Drive link:
https://drive.google.com/drive/folders/1VXn1y-6T7OhEaWhi0U0H8XsECOc6HUTA?usp=sharing

Demo:
The demo video can be accessed by clicking where the video would normally appear in the Final Project Presentation pdf
