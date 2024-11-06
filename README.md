# CalorieAdvisor_GENAI_DOCTOR
Nutritionist Generative AI application which acts as a doctor using Google Gemini Pro Vision

## Overview
**Calorie Advisor** is an AI-powered health app that leverages **Google Gemini Pro Vision API** to analyze the nutritional content of meals. By simply uploading a photo of your food, the app provides an instant breakdown of calories, nutrient content, and evaluates whether the food is balanced. The app is designed to promote healthy eating habits by providing detailed nutritional information for each meal.

## Features
- **Image-based Calorie Estimation**: Upload photos of your meals to receive an analysis of total calories and specific nutrient content.
- **Nutritional Breakdown**: Provides a detailed nutrient composition, including carbohydrate, protein, fat, fiber, and sugar percentages.
- **Health Recommendations**: Evaluates if the food is balanced and offers insights into nutrient distribution, highlighting any nutritional imbalances.

## Motivation
This app was inspired by the importance of healthy eating. Monitoring nutrient intake and calorie consumption can help in achieving a balanced diet, supporting long-term health and well-being. This app serves as a digital nutritionist, helping users make informed dietary choices.

## Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone [repo URL]
   cd CalorieAdvisor

## Install dependencies:
**Install required libraries from requirements.txt:**

pip install -r requirements.txt

## Set up your API Key:
**Go to Google Maker Suite to generate an API key for Gemini Pro Vision.**

Store the API key in a .env file in this format:

GOOGLE_API_KEY=your_api_key_here
