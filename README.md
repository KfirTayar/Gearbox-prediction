# Gearbox Prediction - A Classification Project

This project focuses on predicting the **gearbox type** (Automatic, Manual, or Tiptronic) of second-hand cars using machine learning classification models.  
A **web crawler** was developed to collect a dataset, which is then used for **data analysis, feature engineering, and model training**.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Results](#results)

## Project Overview

This is a **classification project** that predicts the **gearbox type** (Automatic, Manual, or Tiptronic) of second-hand cars.  
The dataset was created using a **custom web crawler**, and various **machine learning models** were tested to find the best classifier.  
The project involves **data preprocessing, feature selection, and model evaluation**.

## Dataset

The dataset consists of second-hand car listings scraped from a website.  
It includes the following **features**:

| Feature        | Description                                       |
|---------------|---------------------------------------------------|
| **Year**      | Year of manufacture                              |
| **Model**     | Car make and model                               |
| **KM**        | Total mileage (kilometers driven)                |
| **Hand**      | Number of previous owners                        |
| **CM**        | Engine volume (in liters)                        |
| **Color**     | Car color                                        |
| **Area**      | Geographic location of the car                   |
| **Gearbox**   | **Target variable**: Automatic, Manual, Tiptronic |
| **Price**     | Car's listed price                               |
| **IsNew**     | Whether the car is new (1 = Yes, 0 = No)         |
| **IsSaved**   | If the car is marked as saved (1 = Yes, 0 = No)  |
| **WithoutAccidents** | Whether the car has accident history (1 = No accidents, 0 = Had accidents) |

## Results

**Best Model Performance:**
The best model achieved an accuracy of 90%, successfully classifying cars into Automatic, Manual, or Tiptronic.