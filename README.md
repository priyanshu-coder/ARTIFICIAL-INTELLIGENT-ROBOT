# ARTIFICIAL-INTELLIGENT-ROBOT

In this work, a non-linear model is prepared for a mobile robot for detecting an obstacle and avoiding it using Artificial Neural Network with an accuracy of 98.2%. Here Robot uses Raspberry Pi Zero W and Node MCU as microcontroller and employs one ultrasonic distance sensor and two Infrared sensors.

This work contributes a powerful and a well-trained model that can be used for an autonomous robot for real-time navigation in a complex environment. This model is prepared through neural networks using Backpropagation algorithm with great accuracy.

ROBOT:


![WhatsApp Image 2019-06-25 at 11 45 30 PM](https://user-images.githubusercontent.com/52497145/61578037-1adb9200-ab0e-11e9-8621-778b5151bd27.jpeg)

Our preparation of the model is divided into three parts:

1. Firstly we collect our training data by randomly navigating our robot in an environment containing obstacles and navigation is done through software connected to Node MCU controlling its motor driver. Data is in the format of a distance of the obstacle from the ultrasonic sensor, the velocity of the right wheel and velocity of the left wheel, velocity is measured using infrared sensors.

2. Secondly, data is cleaned, all the ambiguous values are deleted and clean data is obtained for training a model. 

3. Lastly, a model is trained using Artificial Neural Network and fitted in the robot to avoid obstacles in real-time and reach the desired location.It can be achieved through Neural Network using Backpropagation algorithm to recognize obstacles in the environment and control its speed. 

DESIGN:

![STRUCTURE](https://user-images.githubusercontent.com/52497145/61578020-c0dacc80-ab0d-11e9-80e4-799729916243.png)
