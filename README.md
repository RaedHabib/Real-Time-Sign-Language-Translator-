# NTI Final Project Real Time Sign Language Translator
![Picture1](https://github.com/RaedHabib/Real-Time-Sign-Language-Translator-/assets/127057461/95a25ae1-8e23-4c3b-ad1e-5ec67a5f74dc)

# About:
This project was submitted by my team as the final project of the NTI's Digital Egypt Youth – Initiative, Artificial Intelligence (AI) and Internet of Things (IoT) Modules.



We would like to thank our mentors Dr. Mohamed Zorkany and Dr. Iman Sayed for giving us the opportunity to undertake the project. We thank them for their immense guidance, and appreciate their timely engagement.
We would like to extend special gratitude to the “National Telecommunication Institute” for giving us the opportunity to participate in this great initiative.


The inability to speak is considered to be a true disability. People with this disability use different modes to communicate with others, there are several methods available for their communication one such common method of communication is sign language. 

Developing sign language applications for deaf people can be very important, as they’ll be able to communicate easily with even those who don’t understand sign language. Our project aims to take the basic step in bridging the communication gap between normal people, deaf and dumb people using sign language.

The main focus of this work is to create a vision-based system to identify sign language gestures from video sequences in real-time. The reason for choosing a system based on vision relates to the fact that it provides a simpler and more intuitive way of communication between a human and a computer. In this project, around 30 different gestures have been considered. 

We used the following approach for the classification of sign language gestures:
We have used the the VGG model, a deep CNN (convolutional neural net) to train the model. CNN was trained on the images obtained from the captured data set of train data. A trained CNN model was used to make predictions for individual frames to obtain a sequence of predictions or pool layer outputs for each gesture. The data set used consists of American Sign Language (ASL) Gestures, with 28,967 images belonging to about 30 gestures. Using the predictions by CNN, an accuracy of 100% was obtained.
