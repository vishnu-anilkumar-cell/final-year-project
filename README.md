  # Final Year Project: E-MOGRAM

**E-MOGRAM** is a sentiment analysis-based mental health support system developed as part of my final year BCA project. It uses pre-trained NLP models to analyze social media content and provide emotional insights through mobile applications for both users and doctors.

## Project Overview

This project is composed of three main components, each hosted in a separate repository:

### 1. [e-mogram](https://github.com/vishnu-anilkumar-cell/e-mogram)
- **Type:** Backend (Django)
- **Features:**
  - Fetches social media posts and captions
  - Performs sentiment analysis using VADER and Hugging Face pre-trained models
  - Stores user data and analysis results in SQLite
  - Sends emotional alerts via Firebase

### 2. [wellnest-main](https://github.com/vishnu-anilkumar-cell/wellnest-main)
- **Type:** Flutter mobile app for users
- **Features:**
  - User registration and login
  - View personal sentiment trends
  - Get recommendations or alerts based on sentiment

### 3. [wellnest_doctor-main](https://github.com/vishnu-anilkumar-cell/wellnest_doctor-main)
- **Type:** Flutter mobile app for doctors
- **Features:**
  - Doctor login
  - View sentiment data of assigned users
  - Provide suggestions or initiate contact

## Technologies Used
- **Frontend:** Flutter (for both apps)
- **Backend:** Python, Django, SQLite
- **NLP Models:** VADER, Hugging Face Transformers
- **Firebase:** Notifications
- **Version Control:** Git & GitHub

## Setup & Deployment
Each repository contains its own README with instructions to clone, set up, and run the respective component.

## Developer
**Vishnu Anilkumar**  
Bachelor of Computer Applications (BCA)  
Sacred Heart College, Kochi  
GitHub: [@vishnu-anilkumar-cell](https://github.com/vishnu-anilkumar-cell)

---
