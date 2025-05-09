# Riyadh-POI-Cleaning-and-Feature-Engineering

This notebook documents the data cleaning, preprocessing, and feature engineering steps for our graduation project:  
**"Personalized Points of Interest (POI) Recommendation System for Tourism in the Capital City of Saudi Arabia – Riyadh."**  
It focuses on preparing a high-quality dataset from manually collected Swarm check-ins, enabling effective training of hybrid recommendation models.

> This work was developed as part of our **Graduation Project – AI Track, College of Computer Science and Information Technology**.

---

## Project Objectives

- Clean and preprocess user check-in data from Swarm (Foursquare)  
- Engineer spatial, temporal, and behavioral features  
- Prepare structured input suitable for deep learning and graph-based recommendation models  

---

## Dataset

- **Source**: Manually collected check-ins from the **Swarm app (Foursquare)**  
- **Type**: Location-based user check-in data from Riyadh  
- **Attributes**:  
  - `User ID`, `Venue ID`, `Venue Name`, `Latitude`, `Longitude`  
  - `Check-in Time`, `Day`, `Previous Venue`, `Venue Category`  
- **Preprocessing**:  
  - Cleaned missing and duplicate entries  
  - Parsed datetime to extract time-based features  
  - Encoded venue categories and user behavior  
  - Normalized latitude and longitude for clustering  

The dataset was manually compiled in a single structured file containing rich temporal, spatial, and behavioral attributes.

---

## Processing Pipeline

The data pipeline includes:
- Handling missing values, duplicates, and data type issues  
- Extracting features such as:
  - Hour of day, Day of week, Weekday/Weekend
  - Distance between consecutive venues
  - Stay duration and previous venue behavior  
- One-hot encoding categorical variables like venue category  

---

## Key Contributions

This was a **collaborative graduation project**, and all team members participated in collecting and organizing the raw data from Swarm.

I was responsible for:
- Data cleaning and formatting  
- Preprocessing and transformation steps  
- Feature engineering to enrich the dataset for model training  

These efforts ensured that the dataset was accurate, structured, and fully prepared for use in our hybrid recommendation system.

---

## Project Team

- **Joud Aldhuwaihi**  
- **Munirah Almutlaq**  
- **Mayyan Alharbi**  
- **Watin Abdullah Aljohani**  
- **Fatimah Albuainain**  

**Supervised by**:  
- Dr. May Aldossary  
- Dr. Fatemah Alghamedy  
