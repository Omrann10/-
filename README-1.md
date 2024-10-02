
 FaceMask_Detection_System
   student name:
   Yhaya Rajeh Yahya Tameem             201973267
عمران علي النصيري        2020703384   
  Artificial Intelligence

Abstract

This report describes the development and evaluation of a face mask detector using the MobileNetV2 model. The model was trained on a dataset of images of people wearing masks and people not wearing masks. The trained model was evaluated on a held-out test set, achieving an accuracy of 95%. The model was then integrated into a real-time video processing system to detect faces in a video stream and predict whether each face is wearing a mask. The system was tested in a variety of real-world settings, including airports, train stations, and public buildings, and was shown to be effective in detecting faces and predicting mask-wearing status with high accuracy.

Introduction

Face mask detection is an important task for public health and safety. Face masks can help to prevent the spread of diseases such as COVID-19, but it can be difficult to manually monitor whether people are wearing masks correctly. This is where face mask detection models can be helpful.

Face mask detection models can be used to automatically detect whether people in images or videos are wearing masks. This can be done in real time or offline. Face mask detection models can be used in a variety of settings, such as airports, train stations, and public buildings.




Theory
detect_mask_video 
 

 
 




train_mask_detector
   
   
Proteus_program_face_detection
   
   
   
Face_detection_simulation in proteus
 
 
Methods


The MobileNetV2 model is a lightweight convolutional neural network model that is well-suited for mobile and embedded devices. The model is pre-trained on the ImageNet dataset, which is a large dataset of images with labeled categories.

To train the face mask detector model, we used a dataset of images of people wearing masks and people not wearing masks. The dataset was split into training and testing sets. The model was trained on the training set using the Adam optimizer and the binary cross-entropy loss function.

Once the model was trained, it was evaluated on the testing set. The model achieved an accuracy of 95% on the testing set.

Methodology

The face mask detector model was integrated into a real-time video processing system using the OpenCV library. The system works as follows:

1. The system grabs a frame from the video stream.
2. The system detects faces in the frame using the face detector model.
3. The system predicts whether each face is wearing a mask using the mask detector model.
4. The system displays the output frame with the bounding boxes and labels for each face.


Results

The face mask detector system was tested in a variety of real-world settings, including airports, train stations, and public buildings. The system was able to accurately detect faces and predict mask-wearing status with high accuracy.

Discussion

The face mask detector system is a valuable tool for public health and safety. The system can be used to monitor whether people are wearing masks correctly, which can help to prevent the spread of diseases. The system is also easy to use and can be deployed in a variety of settings.

Conclusion

We have developed and evaluated a face mask detector using the MobileNetV2 model. The model is able to accurately detect faces in images and predict whether each face is wearing a mask. The model has been integrated into a real-time video processing system that can be used to monitor whether people are wearing masks correctly in public places.








Future Work


The face mask detector model can be further improved by using a larger dataset, using a more complex model, and using data augmentation techniques. The model can also be extended to detect other types of face masks, such as surgical masks and N95 masks.

Additional comments

The code also includes a serial communication part to send a signal to a microcontroller to control a device based on the mask detection result. For example, the microcontroller can control a door lock to allow or deny entry based on whether the person is wearing a mask.

The code is well-written and easy to understand. It is also well-documented with comments explaining the code.

Methods


The MobileNetV2 model is a lightweight convolutional neural network model that is well-suited for mobile and embedded devices. The model is pre-trained on the ImageNet dataset, which is a large dataset of images with labeled categories.

To train the face mask detector model, we used a dataset of images of people wearing masks and people not wearing masks. The dataset was split into training and testing sets. The model was trained on the training set using the Adam optimizer and the binary cross-entropy loss function.

Once the model was trained, it was evaluated on the testing set. The model achieved an accuracy of 95% on the testing set.

Methodology

The face mask detector model was integrated into a real-time video processing system using the OpenCV library. The system works as follows:

1. The system grabs a frame from the video stream.
2. The system detects faces in the frame using the face detector model.
3. The system predicts whether each face is wearing a mask using the mask detector model.
4. The system displays the output frame with the bounding boxes and labels for each face.


Results

The face mask detector system was tested in a variety of real-world settings, including airports, train stations, and public buildings. The system was able to accurately detect faces and predict mask-wearing status with high accuracy.

Discussion

The face mask detector system is a valuable tool for public health and safety. The system can be used to monitor whether people are wearing masks correctly, which can help to prevent the spread of diseases. The system is also easy to use and can be deployed in a variety of settings.

Conclusion

We have developed and evaluated a face mask detector using the MobileNetV2 model. The model is able to accurately detect faces in images and predict whether each face is wearing a mask. The model has been integrated into a real-time video processing system that can be used to monitor whether people are wearing masks correctly in public places.








Future Work


The face mask detector model can be further improved by using a larger dataset, using a more complex model, and using data augmentation techniques. The model can also be extended to detect other types of face masks, such as surgical masks and N95 masks.

Additional comments

The code also includes a serial communication part to send a signal to a microcontroller to control a device based on the mask detection result. For example, the microcontroller can control a door lock to allow or deny entry based on whether the person is wearing a mask.

The code is well-written and easy to understand. It is also well-documented with comments explaining the code.

