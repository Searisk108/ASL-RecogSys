# ASL-RecogSys

The main objective of this project is to develop a system that can recognize static as well as dynamic hand signs and convert the generated output to speech in real time. This project works on computer vision-based hand gesture recognition using convolutional neural network and recurrent neural network in Python. This project has three main parts: First, ASL Fingerspelling, in which the ASL alphabets (A-Z) are recognized on the basis of input static hand sign image provided to the system. Trained using CNN VGG-16 model which is pretrained on ImageNet dataset, this system has a test accuracy of 90.47 per cent with loss of 0.33. Second, Text to ASL, in which the text entered by the user is converted into a sequence of images that correspond to individual alphabets of the entered text and provides information to the user about the signs that correspond to various alphabets.And, lastly, ASL words, in which the user can sign a word out of the five available words namely “Yes”, “No”, “Bye”, “Me” and “You” and the system would recognize the word with the help of the dynamic sign and generate speech. Trained using LSTM network, this system has test accuracy of 59.37 per cent with a loss of 1.049. This combined system is also highly dependent on the placement of the camera, background conditions and lightning sensitivity.
You can find the complete project in the link below:

https://drive.google.com/file/d/1YaFlf0N6n8Y20HNjX1xCu-KuD2YdhF06/view?usp=sharing

Contributors:
Amrita Thakur, Pujan Budhathoki, Sarmila Upreti and Shirish Shrestha

Supervisor:
Prof. Dr. Subarna Shakya
