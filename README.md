# NTI---Final-Project-Real-Time-Sign-Language-Translator-
This project was submitted by my team as the final project of the NTI's Digital Egypt Youth – Initiative, Artificial Intelligence (AI) and Internet of Things (IoT) Modules.



We would like to thank our mentors Dr. Mohamed Zorkany and Dr. Iman Sayed for giving us the opportunity to undertake the project. We thank them for their immense guidance, and appreciate their timely engagement.
We would like to extend special gratitude to the “National Telecommunication Institute” for giving us the opportunity to participate in this great initiative.


Inability to speak is considered to be true disability. People with this disability use different modes to communicate with others, there are number of methods available for their communication one such common method of communication is sign language. 

Developing sign language application for deaf people can be very important, as they’ll be able to communicate easily with even those who don’t understand sign language. Our project aims at taking the basic step in bridging the communication gap between normal people, deaf and dumb people using sign language.

The main focus of this work is to create a vision-based system to identify sign language gestures from the video sequences in real time. The reason for choosing a system based on vision relates to the fact that it provides a simpler and more intuitive way of communication between a human and a computer. In this project, around 30 different gestures have been considered. 

We used the following approach for the classification of sign language gestures:
To train the model we have used VGG model which is a deep CNN (convolutional neural net). CNN was trained on the images obtained from the captured data set of train data. Trained CNN model was used to make predictions for individual frames to obtain a sequence of predictions or pool layer outputs for each gesture. The data set used consists of American Sign Language (ASL) Gestures, with 28,967 images belonging to about 30 gestures. Using the predictions by CNN accuracy of 100% was obtained.
