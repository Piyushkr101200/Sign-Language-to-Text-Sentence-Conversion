# Sign-Language-to-Text-Sentence-Conversion

# 1. Introduction
Sign language is one of the oldest and most natural form of language for communication, but since most people do not know sign language and interpreters are very difficult to come by, we have come up with a real time method using neural networks for fingerspelling based American sign language. In our method, the hand is first passed through a filter and after the filter is applied the hand is passed through a classifier which predicts the class of the hand gestures. Our method provides 95.4 % accuracy for the 26 letters of the alphabet. 
American sign language is a predominant sign language Since the only disability D&M people have is communication related and they cannot use spoken languages hence the only way for them to communicate is through sign language. Communication is the process of exchange of thoughts and messages in various ways such as speech, signals, behavior and visuals. Deaf and dumb(D&M) people make use of their hands to express different gestures to express their ideas with other people. Gestures are the nonverbally exchanged messages and these gestures are understood with vision. This nonverbal communication of deaf and dumb people is called sign language.
Sign language is a visual language and consists of 3 major components:
![image](https://user-images.githubusercontent.com/110718114/188227541-f83191f4-e3b3-479b-81d2-ce1f8e565a66.png)

# 2. Objective of the project:
In our project we basically focus on producing a model which can recognize Fingerspelling based hand gestures in order to form a complete word by combining each gesture. The gestures we aim to train are as given in the image below.
![image](https://user-images.githubusercontent.com/110718114/188227684-e73557f2-bc72-4f64-b9ea-dc070db35e30.png)
![image](https://user-images.githubusercontent.com/110718114/188227691-c4648eca-ce7f-4108-9fc4-d0ca693b1c1f.png)
![image](https://user-images.githubusercontent.com/110718114/188227708-13c4614b-5478-4eca-9728-3ede1c7f9b3a.png)

# 3. Libraries used in this Project:
(a)TensorFlow:
TensorFlow is an open-source software library for numerical computation. First, we define the nodes of the computation graph, then inside a session, the actual computation takes place. TensorFlow is widely used in Machine Learning.
(b)Keras: Keras is a high-level neural networks library written in python that works as a wrapper to TensorFlow. It is used in cases where we want to quickly build and test the neural network with minimal lines of code. It contains implementations of commonly used neural network elements like layers, objective, activation functions, optimizers, and tools to make working with images and text data easier.
(c)OpenCV: OpenCV (Open-Source Computer Vision) is an open-source library of programming functions used for real-time computer-vision. It is mainly used for image processing, video capture and analysis for features like face and object recognition. It is written in C++ which is its primary interface, however bindings are available for Python, Java, MATLAB/OCTAVE.

# 4. Block Diagram:
![image](https://user-images.githubusercontent.com/110718114/188228044-8dbf80cd-a81c-47e4-95e4-298c251622c4.png)

CNN Classifier Model
![image](https://user-images.githubusercontent.com/110718114/188232438-b7ac8ee3-e478-4255-85c5-12748391b8b1.png)

# 5. Results & conclusion:
In this report, a functional real time vision based American sign language recognition for D&M people have been developed for asl alphabets. We achieved final accuracy of 95.4% on our dataset. We are able to improve our prediction after implementing two layers of algorithms in which we verify and predict symbols which are more similar to each other.
This way we are able to detect almost all the symbols provided that they are shown properly, there is no noise in the background and lighting is adequate.

# 6. Future scope & advancements:
We are planning to achieve higher accuracy even in case of complex backgrounds by trying out various background subtraction algorithms. We are also thinking of improving the preprocessing to predict gestures in low light conditions with a higher accuracy.

# 7. References:
http://ecasp.ece.iit.edu/publications/2012-present/2021-03.pdf
https://www.semanticscholar.org/paper/American-Sign-Language-Recognition-using-Deep-andBantupalli-Xie/2b0c7196868365fdbeea1742e1731ac43d8a3d6b
https://www.sciencedirect.com/science/article/pii/S1877050920312473/pdf?md5=a4c07e371bbe5d4c4e0d663491bfd2da&pid=1-s2.0-S1877050920312473-main.pdf
