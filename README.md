# Classifier
 A simple HMM cluster classifier
 
 Hand in Motion Recognition
 
 ![demo](https://user-images.githubusercontent.com/33089347/180631238-adabe533-65ad-42b3-ae81-741ac96da216.gif)
 
 Hand gesture recognition from visual images has a number of potential applications in human-computer interaction, machine vision, virtual reality, machine control in industry, and so on. Most conventional approaches to hand gesture recognition have employed data gloves, but for a more natural interface, hand gestures must be recognized from visual images without using any external devices. Our research is intended to draw and edit graphic elements by hand gestures. As a gesture is a continuous motion on a sequential time series, the HMM (hidden Markov model) must be a prominent recognition tool. The most important thing in hand gesture recognition is what the input features are that best represent the characteristics of the moving hand gesture. We consider a planar hand gesture in front of a camera and use 8-directional chain codes as input vectors. 


![gestures](https://user-images.githubusercontent.com/33089347/180631243-f468880b-394a-407d-8d24-ae52c8125e7a.jpg)

For training an HMM network, a simple context modeling method is embedded for training on a "left-to-right" HMM model. This model is applied to drawing and editing specified graphic elements. The overall objective is to recognize 12 different dynamic gestures. In our experiments, we have had good recognition results on a pre-confined test environment: (1) the spotting time is synchronized at the static state of a hand, (2) limb parts other than the hands are motionless, and (3) the change in the hand posture during movement is meaningless. Our system is to be advanced by adopting more diverse input features representing more dynamic features of hand gestures.
 
 
