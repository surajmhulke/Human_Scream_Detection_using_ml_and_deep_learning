
# Human_Scream_Detection_using_ml_and_deep_learning

# Note: This project was not originally created by me. I am working on it, and I have uploaded it here for the purpose of storing it for future reference and development.

This Application predicts human screams in sound file
### read the manual.txt first
Project Acceptance
The research paper has got published at the 5th International Conference on Inventive Systems and Control [ICISC 2021] on the topic of Human Scream Detection through three-stage supervised learning and deep learning.

Team Members
Yash Mathur
Riya Mathur
###### for using this model read manual file which is uploaded with above content

### Features:
* developed in python3
* uses the concept of machine learning and deep learning
* its research paper has got accepted in 5th International Conference on Inventive Systems and Control [ICISC 2021]on the topic Human Scream Detection through three-stage supervised learning and deep learning.
* the main idea to develop such type of application was to reduce crime rate.
Project Title: Human Scream Detection and Analysis for Controlling Crime Rate using Machine Learning and Deep Learning

Crime is the biggest social problem of our society which is spreading day by day. Thousands of crimes are committed every day, and still many are occurring right now also all over the world. A crime occurs in many faces, it can happen in any face like robberies, murders, rapes, aggravated and simple assault, homicide, etc. In many cases the absence of police is observed at crime spots, it may be because they do not have a proper address or sometimes nobody informed them. Therefore, we have tried to address the problem with the help of our project wherein the focus would be to detection of crime on time and help the nearest police station officers to reach on time at the crime spot using location sharing through an alert message in form of SMS ( Short Messaging Service). 

Introduction 
As the title suggests, the project will be a desktop application that has a feature to work in the background itself and by using Machine Learning and Deep Learning concepts, it will detect and analyze human screams in a real-time environment and if this application found something serious in it’s surrounding then it will automatically send alert message to the nearest police station with the location of its user. Not only this, the application will capable to detect clear human sound from the background noise.

Objective: The Objective of this project is to use the advanced technologies in such a way that they can be used to help someone save their life and to control the crime rate.


Tool and Technologies Used:
The whole project back-end is developed using python language
Kivy framework is used in this project to design the interface of the application which is suitable for both desktops as well as Android applications.
SVM (Support Vector Machine) of Machine Learning is used for the detection and classification of screams.
Multilayer perceptrons model of Deep learning is used for the confirmation of detected screams.
Skillset Required:
Core and Advance Python knowledge is mandatory
Basic Kivy framework knowledge is required
SVM (Support Vector Machine) basic knowledge is required in machine learning
Neural networks knowledge is required in machine learning
Must be familiar with libraries such as pandas, NumPy, scikit-learn, TensorFlow, and librosa.
Implementation
Let’s look at the implementation of this project into different steps which are described below:

Step 1: UI design
First, the UI or the user interface of the project is developed. We will develop the UI using Kivy ( Python) framework, which the user will use to interact. Let’s look at the UI of this project.


Main Screen


Recording screen

Step 2: Prepare a data set for Human Scream detection 
The whole data set of this project is divided into two classes one is a positive class which includes around 2000 human screams to train the model and another is a negative class which includes around 3000 negative sounds which are not considered as a scream.

Note: The data set for this project is collected from different websites like https://www.freesoundeffects.com/.

Step 3: Extraction of MFCCs 
The next step is the extraction of MFCCs from the data set using Librosa library and save the extracted MFCCs in a CSV file on your computer. 

Note: MFCCs stands for Mel Frequency Cepstral Coefficients, is a feature that is widely used in automatic speech and speaker recognition.

Step 4: Training of SVM model and its saving
Next, we will train SVM (Support Vector Machine) model over those MFCCs which we had created in the previous step and when the whole training gets completed then we will save it using TensorFlow library. There is a diagram given below for detection of noise, speech, shout and scream using SVM classifier.


Detection of noise, speech, shout and scream using SVM classifier

Step 5: Training of MPN model and its saving
Now, we will train MPN (Multilayer perceptrons model) over sounds present in the data set to get good accuracy of the model and when the whole training gets completed then again save it using TensorFlow library as we do earlier. The working diagram of MPN is given below.


Working of MPN 

Step 6: Approach to generating an alert message
Now, after successfully training and saving both the models, now we will go with the testing of these two models and according to the response provided by both models we will decide the level of risk and according to the risk level, we will generate alert messages.

In this project there are two kinds of alert messages will get generate which are high-risk alert messages and medium risk alert messages based on the conditions in the surrounding.

High-risk alert message: High-risk alert message will get generated by the system in the case when both models will detect the human scream in surroundings.
Medium risk alert message: A medium risk alert message will automatically get generated by the system in the case when one of the two models detects the human scream in the surrounding.
Step 7: Send SMS to nearest Police Station
However, the project is currently under development so we are providing the idea only that how one can develop this feature. For the development of this feature, we can take the help of databases and can send SMS to that number at the time of any emergency detected by the project.

Working diagram
A working diagram of this project is provided to you, which explains the internal working of both models and will be used in implementing the project.


Combined internal working of both models  (SVM and MPN)

Output:


Video Player

00:00
02:05


Project Application in Real-Life
This project is proposed for the safety of society. This project aims to help in reducing the crime rate and also aims to help police in their work a lot. Also, the success of this project will also encourage developers to build something more useful for the safety of society.

Project Acceptance
The research paper has got published at the 5th International Conference on Inventive Systems and Control [ICISC 2021] on the topic of Human Scream Detection through three-stage supervised learning and deep learning.

Team Members
Yash Mathur
Riya Mathur
Github Link: https://github.com/themockingjester/Human_Scream_Detection_using_ml_and_deep_learning

## Have a look on it here:
 
![alt text](https://github.com/themockingjester/Human_Scream_Detection_using_ml_and_deep_learning/blob/main/gifs%20for%20github/demo1.gif)<br>
![alt text](https://github.com/themockingjester/Human_Scream_Detection_using_ml_and_deep_learning/blob/main/gifs%20for%20github/demo2.gif)



