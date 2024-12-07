# Customer Behavior Prediction on E-Commerce Websites

## Project Overview
This project predicts customer behavior on e-commerce platforms by identifying loyal customers and those at risk of churn. It leverages session data, classification techniques (e.g., logistic regression, artificial neural networks), and clustering algorithms (e.g., K-means). The system provides insights into customer churn probability and helps businesses take timely actions to retain valuable customers.

---

![image](https://github.com/user-attachments/assets/18d1759b-f4cd-4dcc-be6b-22ba9a2b2e85)
![image](https://github.com/user-attachments/assets/566053e2-59ba-4ceb-a634-940ea3d12737)




## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Motivation](#motivation)
3. [Features](#features)
4. [System Architecture](#system-architecture)
5. [Tools and Technologies](#tools-and-technologies)

---

## Problem Statement
Customer churn leads to significant revenue loss for e-commerce businesses. This project aims to implement a customer churn prediction system by analyzing session parameters and employing classification techniques. It calculates churn probability to identify customers at risk and provides actionable insights to retain them.

---

## Motivation
- Acquiring new customers is expensive; retaining existing customers is more cost-effective.
- Timely prediction of customer churn can prevent revenue loss and strengthen customer relationships.
- Businesses need robust strategies to identify high-risk customers and engage them proactively.

---

## Features
1. **Customer Classification**:
   - Classifies customers as loyal or at risk of churn using classification algorithms.
2. **Churn Probability Calculation**:
   - Predicts churn severity (High, Medium, Low) using Artificial Neural Networks.
3. **Session Analysis**:
   - Analyzes session parameters like hit rate, cart abandonment rate, and repeat purchase rate.
4. **Visualization**:
   - Provides graphs and reports for customer behavior and churn statistics.
5. **Admin Dashboard**:
   - Enables administrators to monitor customer activity and take actions based on churn predictions.

---

## System Architecture
1. **Presentation Layer**:
   - User-facing website built with HTML, CSS, and PHP for front-end interactions.
   - Flask is used to display churn predictions and analytics.
2. **Business Logic Layer**:
   - Python is used for data processing, classification, and neural network implementation.
3. **Database Layer**:
   - MySQL stores customer data, product details, and session parameters.

---

## Tools and Technologies
- **Front-End**: HTML, CSS, Bootstrap, PHP
- **Back-End**: Python (with Flask, scikit-learn, matplotlib, and other libraries)
- **Database**: MySQL
- **Visualization**: Google Sheets, Pygal for data visualization
