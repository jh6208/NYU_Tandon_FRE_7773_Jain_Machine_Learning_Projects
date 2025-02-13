# [NYU Tandon FRE-7773 Jain] Machine Learning Projects

<img width="1175" alt="截屏2023-05-19 下午4 27 12" src="https://github.com/jh6208/Machine_Learning_Exercises/assets/122949623/61cbb3e0-8d40-4839-b944-6b4dd8dd6891">

The projects deal with common questions in the machine learning field, including classical machine learning, deep learning, and reinforcement learning. Some of the projects also tackle the applications of Financial Engineering, including predicting future market states, designing investment strategies, and image classification.

Here is a short catalog briefly discussing each assignment:

***1. Assignment_1_Stock_Price_Prediction:*** 

This first assignment is just a catch-up of what most of us have learned: using simple linear regression to predict the future stock price of AAPL. The only difference is that in this case, we used stock price returns to do the regression instead of stock prices to increase our prediction accuracy. 

* Category: Applications in Finance

***2. Assignment_2_Investment_1:*** 

This is a short exercise designing an investment strategy in one stock to predict whether the stock price's return the next day is positive or negative. If it is positive, then investors should go long the stock; otherwise, not. This is a common investment strategy in finance; if employed appropriately, investors can make a lot of money.

* Category: Applications in Finance

***3. Assignment_3_Investment_2:***

This assignment uses the rolling regression and Kalman filtering to design a simple pairs trading strategy in the S&P 500 ETF and the Dow Jones Industrial ETF. Even though performing poorly by both methods, this mini project provides a general blueprint for implementing the pairs trading strategy in finance, a standard statistical arbitrage approach adopted by investors to earn a profit.

* Category: Applications in Finance

***4. Assignment_4_SVM:***

This short exercise aims to familiarize newcomers with the Support Vector Machines' application in classification. The majority of contributions of this assignment are from the textbook "Hands-On Machine Learning with Scikit-Learn and TensorFlow.pdf," https://www.clc.hcmus.edu.vn/wp-content/uploads/2017/11/Hands_On_Machine_Learning_with_Scikit_Learn_and_TensorFlow.pdf,  by the author Géron A., and its corresponding github repository https://github.com/ageron/handson-ml2.

* Category: Concept Teachings

***5. Assignment_5_PCA_Applications:***

Being the first assignment in the unsupervised learning field, Assignment 5 utilizes the principal component analysis (PCA) to extract useful features
in predicting the returns for the eign portfolios. It then reports the eign portfolios with the highest returns. The same textbook and Github are helpful enough!

* Category: Applications in Finance

***6. Assignment_6_K_Means_Shrink_Correlations_HRP:***

Assignment 6 is a mix of several things: K means clustering, correlation shrinkage, and the Hierarchical Risk Parity to construct the portfolios in finance. Using HRP to build portfolios in finance is a novel idea and solves the singularity problem of matrices. 

* Category: Concept Teachings & Applications in Finance

***7. Assignment_7_DNN_MNIST:***

This mini project applies deep neural networks (DNNs) to image (clothing) applications. It extracts datasets from MNIST and then builds up
a variety of DNN models to maximize the accuracy of the classification task. The good news is that almost all models did a good job, with accuracies close to 90%!

* Category: Applications in Finance

***8. Assignment_8_DNN_Constructions:***

This assignment takes a deep look into the constructions of the DNNs. It includes five steps: DNN Building Ups, the Applications in Image Classification, Initialization, Optimization, and Regularization. 

* Category: Concept Teachings 

***9. Assignment_9_CNN_Constructions:***

This exercise takes a deep look into the constructions of the Convolutional Neural Networks (CNNs).

* Category: Concept Teachings 

***10. Assignment_10_RNN_Constructions:***

This exercise takes a deep look into the constructions of the Recurrent Neural Networks (RNNs).

* Category: Concept Teachings 

***11. Final_Project_RL_Finance:***

This final project concludes with the course. However, it only focuses on topics we have learned. It investigates another exciting field in machine learning: Reinforcement Learning (RL). Reinforcement Learning involves maximizing the Q-value functions and working backward by taking the action that maximizes future rewards. In this setting, the model-free algorithm, the so-called Q-Learning Black Scholes model, extends the classical Black Scholes model and solves the infamous volatility smile problem in finance. This project explains the code applications of the mathematical methodology of the QLBS model in detail. It describes the key points readers should remember from the QLBS model (stored in the pdf file "QLBS_Model_Review.pdf").
