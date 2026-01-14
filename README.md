# 🔐 TrustCheck AI

TrustCheck AI is an AI-powered system consisting of a Flutter mobile application and a Chrome browser extension that detects real and fake websites using machine learning. The project aims to protect users from phishing attacks, online scams, and fraudulent websites by providing instant and reliable website verification.

## 🚀 Features

- AI-based classification of websites as real or fake  
- Flutter mobile app for easy website verification  
- Chrome extension for real-time detection on Google search results  
- Machine Learning model built using XGBoost  
- URL feature analysis for accurate predictions  
- Clean and user-friendly interface  
- Fast and lightweight system  

## 🧠 How It Works

The system uses an XGBoost machine learning model trained on URL-based features such as URL length, HTTPS usage, special characters, subdomains, suspicious keywords, and character entropy.  
A Flask backend extracts these features from user-provided URLs and returns real-time predictions via an API.

## 🛠️ Tech Stack

- Flutter (Mobile Application)  
- Python  
- Flask (Backend API)  
- XGBoost (Machine Learning Model)  
- Chrome Extension (JavaScript)  

## 📱 Components

- **Flutter App:** Allows users to check website authenticity, view history, and explore known fake websites.  
- **Flask Backend:** Handles feature extraction and ML predictions.  
- **Chrome Extension:** Displays “✅ Real” or “❌ Fake” directly on Google search results.

## 🎯 Purpose

This project is developed to demonstrate the practical use of machine learning, mobile development, and browser-level security in solving real-world cybersecurity problems.

## 📌 Note

This project is intended for educational and portfolio purposes.
