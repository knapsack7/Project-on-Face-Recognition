# Project-on-Face-Recognition
Recognizing the faces while using webCam in RealTime 

# Training Data Collection
   1. Read and show video stream, capture images
   2. Detect Faces and show bounding box (haarcascade)
   3. Flatten the largest face image(gray scale) and save in a numpy array
   4. Repeat the above for multiple people to generate training data


# Recognise Faces using some classification algorithm - like Logistic, KNN, SVM etc.
 1. load the training data (numpy arrays of all the persons)
 2. Read a video stream using opencv
 3. extract faces out of it
 4. use knn to find the prediction of face (int)
 5. map the predicted id to name of the user 
 6. Display the predictions on the screen - bounding box and name
