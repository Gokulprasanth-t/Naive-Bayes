# Naive-Bayes

## Obesity Classification using Naive Bayes

This repository contains the implementation of an Obesity Classification system using Naive Bayes algorithm from scratch. The purpose of this project is to demonstrate the application of the Naive Bayes algorithm for classification tasks, specifically for predicting obesity based on given features.
<hr>


![image](https://github.com/Gokulprasanth-t/Naive-Bayes/assets/121724612/30e2b80b-02e9-42bf-8ab5-85768c647389)


## Introduction

Naive Bayes Classifier is a very popular supervised machine learning algorithm based on Bayes’ theorem. It is simple but very powerful algorithm which works well with large datasets and sparse matrices, like pre-processed text data which creates thousands of vectors depending on the number of words in a dictionary. It works really well with text data projects like sentiment data analysis, performs good with document categorization projects, and also it is great in predicting categorical data in projects such as email spam classification.

It is used to solve many different problem statements, and it is quite fast in training a model since Naive Bayes classifier completely works on probability, so the conversion happens quickly.

<hr>

## Understanding Math and Statistics behind

Bayes’ theorem describes the probability of an event, based on prior knowledge of conditions that might be related to the event.

First, let’s take a formula of conditional probability, and try to derive Bayes Theorem:

![image](https://github.com/Gokulprasanth-t/Naive-Bayes/assets/121724612/059080a5-9510-4170-897d-62292f68bfb0)

where

<b>x1, … , xj</b> are j features that are independent of each other. y is the dependent variable..<br>
<b>P(y|x1,…, xj):</b> Posterior Probability<br>
P(x1, …, xj|y):</b> Likelihood of features x1 to xj given that their class is y.<br>
P(y):</b> Prior Probability<br><br>
P(x1, …, xj): Marginal Probability.<br><br>
<hr>

## Dataset

The dataset  have the following columns:

Age: Age of the individual (numeric).<br>
Height: Height of the individual in centimeters (numeric).<br>
Weight: Weight of the individual in kilograms (numeric).<br>
Gender: Gender of the individual (categorical: Male or Female).<br>
BMI: Body Mass Index (numeric).<br>
Obesity: Class label indicating the obesity level (categorical: Underweight, Normal Weight, Overweight)
