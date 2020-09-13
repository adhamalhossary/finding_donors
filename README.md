# Machine Learning Nanodegree
## Supervised Learning
## Project: Finding Donors for *CharityML*

----
## Introduction

This project was part of my 'Intro to Machine Learning Nanodegree' provided by Udacity. The code and text in this project is a combination of my own work and that of Udacity.

CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. 

With nearly 15 million working Californians, the goal was to build an algorithm that best identifies potential donors and reduce overhead cost of sending mail. This was done by evaluating and optimizing several supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent.

The data for this project is collected from the 1994 U.S. Census, which originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The datset was donated by Ron Kohavi and Barry Becker, after being published in the article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_. You can find the article by Ron Kohavi [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf). The data we investigate here consists of small changes to the original dataset, such as removing the `'fnlwgt'` feature and records with missing or ill-formatted entries.

