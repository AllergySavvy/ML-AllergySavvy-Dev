# Machine-Learning

# AllergySavvy - Machine Learning Development

Welcome to the AllergySavvy Machine Learning Development repository. This project is part of the AllergySavvy app, designed to help users detect food allergies and receive personalized recipe recommendations.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

AllergySavvy is an innovative app aimed at individuals with food allergies. It leverages machine learning algorithms to analyze user data and provide tailored recipes that exclude allergens. This repository contains the machine learning models, data processing scripts, and other development resources for AllergySavvy.

## Features

- **Allergy Detection**: 
  - Uses machine learning models to detect food ingredients that may cause allergies based on user input.
  - This feature leverages algorithms to extract and analyze allergenic ingredients from recipes.

- **Personalized Recipe Recommendations**:
  - Provides personalized recipe recommendations based on the user's preferred ingredients.
  - Utilizes a Word2Vec model to measure the similarity between food ingredients and provide relevant recipe suggestions.

- **Data Processing**:
  - Cleans and processes recipe data to ensure high-quality data before model training.
  - Scripts to merge, group, and convert recipe data into suitable formats for model training.

- **Model Training and Evaluation**:
  - Google Colab for training and evaluating models using processed recipe datasets.
  - Model training using deep learning techniques to produce accurate recipe recommendation models.

- **Interactive Recommendation System**:
  - An interactive recommendation system that allows users to input allergenic and preferred ingredients.
  - The model provides a list of suitable recipes based on user input.

- **Model Conversion**:
  - Scripts to convert trained models into JSON format for further predictions or integration into other applications.

- **Model and Data Serialization**:
  - Saves trained models and related data in a format that can be accessed and reused in the future.
  - This process ensures that models and data can be easily shared or transferred to other environments.

## Installation

To get started with the development environment, follow these steps:

1. Clone the repository:
  git clone https://github.com/AllergySavvy/ML-AllergySavvy-Dev.git
  cd ML-AllergySavvy-Dev
2. Create and activate a virtual environment:
  python3 -m venv venv
  source venv/bin/activate  # On Windows, use venv\Scripts\activate
3. Install the required dependencies:
  pip install -r requirements.txt

## Usage

After setting up the development environment, you can start using the scripts and notebooks in the repository:

  Data Processing: Use the scripts in the data_processing directory to clean and preprocess your data.
  Model Training: Use the notebooks in the notebooks directory to train and evaluate machine learning models.
  Prediction: Use the scripts in the prediction directory to make predictions using the trained models.

## License

This project is licensed under the BANGKIT 2024 Batch 1.
