# Irrigation prediction using Machine-Learning
Hi, I'm Joyeeta Sarkar.
I'm interested in Artificial Intelligence and its fundamentals.
This is my first code in github.
I'm trying to create a project based on AI and ML.

## About the dataset

Our system's primary function is to offer automated water delivery. Farmers are pleased with the autonomous water delivery based on their crops, according to the product experience. Product functionalities include providing water as needed and automatically activating the relay motor. Real-time sensing and control, self-regulation, and total removal of man power are product characteristics. Farmers who can autonomously give water to different crops based on their needs are examples of customer revalidation.

## Abstract

Irrigation is critical to the success of a garden and farm. The days of manually watering or depending on a friend to water your plants while you are away on vacation or business are long gone. This proposal offered an embedded system for irrigation control. When you are on vacation, you may water your plants on a regular basis. The system includes a wireless sensor network for real-time sensing and control of an irrigation system. This system offers regular and needed levels of water for the garden and farm while minimising water waste. This method is meant to develop an automatic irrigation mechanism that turns the pumping motor ON and OFF based on the moisture content of the ground.

In this system, we connect the Arduino board to the soil moisture sensor, the dht11 sensor, and the NodeMCU. I'm using ML algorithms to detect soil dryness and anticipate water requirements or pump on-off predictions for the next water cycle, and the android application is also available from a distant location for automation.

## Aim and Objective

The primary goal of this project is to create an intelligent irrigation system that analyses soil moisture and assists in deciding whether to switch on or off the water supply. The goal of this project is to offer an autonomous watering system for plants, which will aid in water conservation. The primary goal of this initiative is to eliminate human labour while also conserving water and the environment.

## Applied Algorithms

1) The model for the **KNN (K-Nearest Neighbors)** technique is the whole training dataset. When a prediction for an unknown data instance is required, the KNN method will explore the training dataset for the k-most comparable examples. The most comparable examples' prediction attributes are aggregated and returned as the forecast for the unknown instance. The similarity metric is affected by the type of data. The Euclidean distance may be applied to real-valued data. Hamming distance may be used to other forms of data, such as category or binary data.
•In the case of regression issues, the projected attribute's average may be returned. When it comes to categorization, the most common class may be returned.

2) The **Naive Bayes Algorithm** is a straightforward way for making predictions that employs the probability of each attribute belonging to each class. If you wanted to model a predictive modelling issue probabilistically, you would use supervised learning. •Naive Bayes simplifies the computation of probabilities by assuming that the likelihood of any attribute belonging to a particular class value is independent of all other characteristics. This is a big assumption, yet it yields a quick and effective technique.

•The conditional probability is the likelihood of a class value given an attribute value.We may calculate the chance of a data instance belonging to a class by multiplying the conditional probabilities for each attribute for a particular class value.

•To create a forecast, we can compute the probabilities of each class's instances and choose the class value with the highest probability.

•Because ratios are simple to describe and compute, Naive Bayes is frequently discussed using categorical data. For our purposes, a more relevant version of the method allows numeric characteristics and assumes that the values of each numerical attribute are regularly distributed (fall somewhere on a bell curve). Again, this is a bold assumption, but it yields a reliable outcome.

#### Refer Test_code.ipynb for the test code
