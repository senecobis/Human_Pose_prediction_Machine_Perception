# Human_Pose_prediction_Machine_Perception
Future human pose estimation, from frame to frame motion

Introduction
Predicting how human motion evolves in the short-term future is a task that has many applications in human-computer interaction, computer vision, or robotics and is an important building block in systems used for autonomous navigation (e.g. self-driving cars).
 
 
Human motion data can come in many forms. In this project, we are working with skeletal representations, i.e. we represent the human body as a set of its major joints which is organized in a tree-like, hierarchical chain that defines how the joints are linked together. Each joint is parameterized as a rotation that defines how one bone segment must be rotated to obtain the orientation of the following bone segment.


Task
Given sequences of pre-recorded human motion data and your task is to predict how the motion continues for several frames in the future. You are expected to train and evaluate several models that solve this task. Along with the data, you will receive a skeleton code written in pytorch that can load the data, train a dummy neural network and visualize predictions. The code is only meant as a guideline; you are free to modify it to whatever extent you deem necessary. 


Further Reading
Martinez et al. (2017) On Human Motion Prediction Using Recurrent Neural Networks
Wang et al. (2018) Adversarial geometry-aware human motion prediction
Aksan et al. (2019) Structured Prediction Helps 3D Human Motion Modelling
Mao et al. (2019) Learning Trajectory Dependencies for Human Motion Prediction
Mao et al. (2020) History Repeats Itself: Human Motion Prediction via Motion Attention


