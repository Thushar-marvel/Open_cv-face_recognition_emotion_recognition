# OpenCV face recognition emotion recognition

# Face detection

Face detection is a computer technology being used in a variety of applications that identifies human faces in digital images. 
With face detection, you can get the information you need to perform tasks like embellishing selfies and portraits, or generating avatars from a user's photo. Because ML Kit can perform face detection in real time, you can use it in applications like video chat or games that respond to the player's expressions

 # Algorithms Used in this project
 
 Haar cascade FrontalFace 
 Fisher face Recognizer
 Local binary patterns histograms
 Deep learning model
 
 First of all make sure you have OpenCV installed 
  
   ![image](https://user-images.githubusercontent.com/69953585/110933038-3eda8f80-8352-11eb-983a-2b60c5e6f5de.png)
  
   # Haar cascade FrontalFace 
 
 Face detection using Haar cascades is a machine learning based approach where a cascade function is trained with a set of input data. 
 It is basically adaboosting learning algorithm.The algorithm is proposed by Paul Viola and Michael Jones.
 
 In this algorithm predefined features/windows are made to convolve over image. If feature best fit over the image then there is a chance that it is a face.
 Only relevant features are selected while processing the image
 
   ![image](https://user-images.githubusercontent.com/69953585/110933581-f2438400-8352-11eb-89d9-72a326c5392e.png)
 
 # Fisher face Recognizer
 
 Fisherfaces algorithm extracts principle components that separates one individual from another. So ,now an individual's features can't dominate another person's features.
 This method will be applied to generate feature vector of facial image data used by system and then to match vector of traits of training image with vector characteristic of           test image using euclidean distance formula 
 
   ![image](https://user-images.githubusercontent.com/69953585/110934197-b6f58500-8353-11eb-967f-d140f57f71d2.png)


 # Local Binary Pattern (LBP)

 Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the  result as a binary number.It doesn't look at image as a whole, but instead tries to find its local structure by comparing each pixel to its neighboring pixels.

   ![image](https://user-images.githubusercontent.com/69953585/110934075-93cad580-8353-11eb-85fd-cadeb22123e1.png)
   ![image](https://user-images.githubusercontent.com/69953585/110934114-9cbba700-8353-11eb-92ce-afaee46ec0bf.png)
   ![image](https://user-images.githubusercontent.com/69953585/110934099-99282000-8353-11eb-8116-046dd195d133.png)

 # Deep learning model

 CNN has become a state of art for image classification and object detection task.There are many object detection algorithms are available like YOLO,SSD, R CNN,Faster R CNN etc
 Training a object detection model with set of annoted face images will help in real time face detection purpose.It requires more images and also hogh computational power.
 Face detection using ssd model and classification using CNN explanation is given [here](https://github.com/Thushar-marvel/Face_mask_detection)



 ![image](https://user-images.githubusercontent.com/69953585/110934586-308d7300-8354-11eb-986a-c2d0a0a82f19.png)

 # Procedure

  # Import required libraries
 
  Open cv, numpy , tensorflow
 
  # Creating custom data set of face images
 
   Using open cv library python script is written to capture images of face and save it in the directory.
  
   ![image](https://user-images.githubusercontent.com/69953585/110936867-89aad600-8357-11eb-8743-29735f39d800.png)

 
  
  
   # Pre processing the images and training the model
  
   The saved face images are converted to gray scale image
        ![image](https://github.com/Thushar-marvel/Open_cv-face_recognition_emotion_recognition/blob/main/images/Screenshot%20(125).png)
        ![image](https://github.com/Thushar-marvel/Open_cv-face_recognition_emotion_recognition/blob/main/images/Screenshot%20(126).png)
   
   
   Trained Fisher face and LBPH model
   Building object detection model using deep learning from scratch will be explanied in other repository(face detector using ssd)
   Building CNN based face classification model is explained in other repository
   Haarcascade.xml  is used for face detection and LBPH,Fisher face and CNN model is used for face classification task
   
   ![image](https://github.com/Thushar-marvel/Open_cv-face_recognition_emotion_recognition/blob/main/images/Screenshot%20(116).png)
   
   The task is for face detection and classification
   
   # Face emotion recognition 
   
   Install library
   
   ![image](https://user-images.githubusercontent.com/69953585/110942943-8ec05300-8360-11eb-8394-bdfe8327bfdd.png)
   
   This library consists of set of emotions it detect face and classify emotions like happy,sad,angry,neutral,suprise,fear.
       ![image](https://github.com/Thushar-marvel/Open_cv-face_recognition_emotion_recognition/blob/main/images/Screenshot%20(127).png)
   

   
   
   
   
   
 



