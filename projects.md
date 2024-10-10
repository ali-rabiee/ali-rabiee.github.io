---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
classes: wide smaller-font
---

## STREAMS: Self-Training Robotic End-to-end Adaptive Multimodal Shared autonomy
STREAMS is a deep reinforcement learning framework that combines environment data and user input to produce smooth, stable end-effector trajectories for assistive robots, achieving a 96% success rate in simulations and 83% in user studies without requiring pre-existing datasets. [GitHub Link](https://github.com/ali-rabiee/STREAMS)

<video width="600" height="400" controls>
    <source src="{{ '/assets/videos/STREAMS_demo.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag. You can <a href="{{ '/assets/videos/STREAMS_demo.mp4' | relative_url }}">download the video</a> instead.
</video>


## Kinova RL: a ROS package for Shared Control Deep Reinforcement Learning
This ROS package implements a shared control Deep Reinforcement Learning (DRL) system for robotic manipulation
using a Kinova robotic arm. The system integrates visual input from a camera, head motion data from an IMU
sensor, and a trained DQN (Deep Q-Network) agent to control the robot’s actions. [GitHub Link](https://github.com/ali-rabiee/Kinova_RL)

<video width="600" height="400" controls>
    <source src="{{ '/assets/videos/sim2real.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag. You can <a href="{{ '/assets/videos/sim2real.mp4' | relative_url }}">download the video</a> instead.
</video>


## MAGnet: Magnetic Actuation for Guided Neurorehabilitation
This project introduces a novel approach to actuating rehabilitation robots using magnetic technology as a haptic force generator, combined with an Extended Kalman Filter for precise tracking and disturbance compensation in upper-limb motor rehabilitation. The study demonstrates improved smoothness, comfort, and safety in motor training, paving the way for more efficient and user-friendly rehabilitation technologies. 

<video width="600" height="400" controls>
    <source src="{{ '/assets/videos/Kalman1.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag. You can <a href="{{ '/assets/videos/Kalman1.mp4' | relative_url }}">download the video</a> instead.
</video>


## Adaptive Robotic Control for Users with Severe Impairments using DRL
A system that optimizes mapping from low-DoF inputs to high-dimensional robotic actions, enabling
intuitive control for users with severe impairments. It uses adaptive goal prediction and reinforcement learning to
guide actions in real-time, seamlessly blending user input with autonomous assistance. [GitHub Link](https://github.com/ali-rabiee/amplification_DRL)

![GIF]({{ '/assets/videos/amplification_demo.gif' | relative_url }})


## Dual-Mode Robotic Arm Control with GUI and IMU Integration
This project integrates a graphical user interface (GUI) with an inertial measurement unit (IMU) sensor to provide
dual-mode control of a robotic arm. Users can choose to control the robotic arm by clicking on cursor buttons in the
GUI or by using the IMU sensor to move the cursor for button selection. [GitHub Link](https://github.com/ali-rabiee/ClickMove-Robotics)

<img src="{{ '/assets/videos/ClickMove_demo.gif' | relative_url }}" alt="Project 1 GIF" width="600" height="auto">


## Real-time Face Orientation Detection
Developed a real-time video processing application that detects human faces and determines the orientation of the
head for robot control applications. [GitHub Link](https://github.com/ali-rabiee/RealTimeFaceOrientation)

<img src="{{ '/assets/videos/FaceOrientation_demo.gif' | relative_url }}" alt="Project 1 GIF" width="600" height="auto">


## Autonomous vision-based reach-to-grasp DQN agent
An autonomous vision-based reach-to-grasp system using a Deep Q-Network (DQN) agent for robotic arm control. This project utilizes real-time visual input to enable efficient and adaptive grasping in dynamic environments. [GitHub Link](https://github.com/ali-rabiee/Auto-Vision-Grasp)

<img src="{{ '/assets/videos/auto_grasp.gif' | relative_url }}" alt="Project 1 GIF" width="700" height="auto">


## CartPole solution using DQN
his project implements a Deep Q-Network (DQN) to solve the CartPole-v1 environment from OpenAI Gym. The CartPole problem involves balancing a pole on a moving cart. This implementation uses a DQN to learn a policy that keeps the pole balanced for as long as possible. [GitHub Link](https://github.com/ali-rabiee/CartPole-DQN)

<img src="{{ '/assets/videos/cartpole.gif' | relative_url }}" alt="Project 1 GIF" width="700" height="auto">

## Panorama Creation via Harris Corner Detection and Image Stitching
This project involves the creation of panoramic images by detecting key interest points in multiple images using the
Harris corner detector. After identifying these points, the project matches them between images and computes the
homography to accurately align and stitch the images together, resulting in panoramic views. [GitHub Link](https://github.com/ali-rabiee/Keypoint-Extraction-and-Matching)

<img src="{{ '/assets/images/panorama.png' | relative_url }}" alt="Project 1 GIF" width="700" height="auto">

## EEG Data Analysis
Developed a Python-based toolkit for processing and analyzing complex EEG datasets (64 channels, 640 time points,
99 trials). Implemented advanced signal processing techniques including epoch extraction, ERP computation, peak
time identification, topographical mapping, and Laplacian filtering for enhanced spatial resolution. [GitHub Link](https://github.com/ali-rabiee/Brain-Signal-Analysis-Topomaps)

<img src="{{ '/assets/images/EEG.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">

## IMDB Sentiment Analysis
Implemented a comprehensive sentiment analysis pipeline on the IMDB dataset, employing various text preprocessing
techniques (stop word removal, stemming, lemmatization). Developed and compared multiple classification models for
sentiment prediction, and evaluated different clustering methods to uncover patterns in the dataset. [GitHub Link](https://github.com/ali-rabiee/sentiment-analysis)

<img src="{{ '/assets/images/sentiment.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">

## GAN and DCGAN Implementation for Synthetic Digit Generation
Implemented Generative Adversarial Networks (GAN) and Deep Convolutional GANs (DCGAN) to synthesize realistic handwritten digits. Trained models on the MNIST dataset, comparing the performance and quality of generated images between standard GANs and DCGANs. Demonstrated proficiency in deep learning architectures, image generation techniques, and evaluating generative model outputs. [GitHub Link](https://github.com/ali-rabiee/GAN-digits)

<img src="{{ '/assets/images/digits.png' | relative_url }}" alt="Project 1 GIF" width="500" height="auto">
