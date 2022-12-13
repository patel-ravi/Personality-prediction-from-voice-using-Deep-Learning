# Personality_Prediction_From_Voice_using_Deep_Learning

This project attempts to predict the personality traits of a speaker based on the voice, as perceived by people listening to the person for the first time. It was developed as an academic group project for the course 11-785 Introduction to Deep Learning (Spring 2022) at CMU.

Team members: Ravi Patel, Chris Weddle, Mustafa Yilmaz, Haoyu Zhang

Voice has a significant impact on how the personality traits of a speaker are perceived by people. There is substantial research performed regarding the association between a person’s personality and their linguistic features like voice. Utilizing this association between the voice of a person and the personality traits, this project attempts to predict the personality traits of a speaker based on the voice, as perceived by people listening to the person for the first time. 

The five personality traits we aim to predict are Extraversion, Agreeableness, Conscientiousness, Neuroticism, and Openness. Three different models are used for this analysis.
1. Convolutional Neural Network (CNN)
2. An extension of a Convolutional Neural Network with feature mixing and spatial mixing components
3. Long-Short Term Memory (LSTM) network. 
Baseline: Logistic regression

The models perform joint probability predictions on the five personality traits. All found some improvement when compared to a logistic regression implementation, especially the extended CNN model.

This repository contains 6 python notebooks (developed on Jupyter Notebook) each implementing the above mentioned architectures and the baseline method using logistic regression.
