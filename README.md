# Smart-Diet-Recommendation-Based-on-Body-Type-Activity-Level
Smart Diet Recommendation Based on Body Type &amp; Activity Level is a personalized system that suggests healthy diet plans by analyzing a user’s body type and daily activity level. It helps users achieve fitness goals like weight loss or muscle gain through data-driven nutrition guidance.
🥗 Smart Diet Recommendation System
Complete Frontend + Backend | Machine Learning Powered | Deployed with Gradio
📌 Project Overview

The Smart Diet Recommendation System is an intelligent, machine learning–based web application that provides personalized diet recommendations by analyzing a user’s body type, BMI, activity level, fitness goal, and dietary preference. The system is designed to overcome the limitations of generic diet plans by offering customized nutritional guidance tailored to individual physical and lifestyle characteristics.

This project includes both backend model training and a fully interactive frontend, all implemented in Google Colab, making it easy to run, test, and deploy without any external software installation.

🎯 Objectives

To recommend an optimal diet plan based on body type and activity level

To calculate BMI and analyze its impact on nutrition

To use machine learning for accurate diet classification

To provide a user-friendly web interface for real-time predictions

🧠 System Architecture

The system follows a complete end-to-end pipeline:

Synthetic Dataset Generation
A dataset of 5000 samples is generated with attributes such as age, gender, height, weight, BMI, body type, activity level, fitness goal, diet preference, and macronutrients.

Data Preprocessing

BMI calculation

Label encoding for categorical variables

Feature scaling using StandardScaler

Model Training
A Random Forest Classifier is trained to predict the most suitable diet category.
The model achieves ~92% accuracy, ensuring reliable recommendations.

Prediction Logic
The system automatically:

Detects body type from BMI (if selected)

Predicts the ideal diet plan

Displays confidence score, BMI value, calorie estimate, and sample meal

Frontend Deployment
A clean and interactive Gradio web app allows users to input their details and instantly receive diet recommendations.

✨ Key Features

Machine Learning–based diet prediction

Automatic BMI calculation & body type detection

Activity-level–aware recommendations

Personalized calorie estimation

Sample meal suggestions

Confidence score for predictions

Fully interactive web interface

One-click deployment using Google Colab

🛠️ Technologies Used

Python

Scikit-learn (Random Forest Classifier)

Pandas & NumPy

Gradio (Frontend UI)

Google Colab (Execution & deployment)

📊 Output Details

The system provides:

✅ Recommended Diet Plan

📊 Prediction Confidence

📏 Calculated BMI

🔥 Estimated Daily Calories

🍽️ Sample Meal Suggestions

🚀 Applications

Fitness and health platforms

Personalized nutrition planning

AI-based healthcare projects

Student ML & AI portfolios

Academic mini & major projects

🔮 Future Enhancements

Integration with real-world nutrition datasets

Deep learning–based recommendations

Weekly meal planning

Mobile app deployment

Integration with fitness trackers

✅ Conclusion

The Smart Diet Recommendation System demonstrates how machine learning and web technologies can be combined to create an intelligent, real-world health application. By providing personalized, accurate, and explainable diet recommendations, this project highlights the practical impact of AI in healthcare and lifestyle management.
