# 🎬 Movie Recommendation System using Basic Filtering

## 📌 Project Overview
This project demonstrates the implementation of a **Movie Recommendation System using basic filtering techniques**. It recommends movies based on **genre, popularity, and rating (vote average)** using a real-world movie dataset.

The system shows how simple data filtering can be used to suggest relevant movies without using complex machine learning models.
This project was developed as part of the **Machine Learning Internship Program at Horizon Intern**.

## 🎯 Objectives
- Analyze movie dataset  
- Perform basic data filtering  
- Recommend movies based on:
  - Genre  
  - Rating (Vote Average)  
  - Popularity  
- Build a simple recommendation system using Python  

## 📊 Dataset Information
| Attribute        | Details |
|------------------|--------|
| Dataset          | TMDB Movie Dataset |
| Records          | 5000+ |
| Features         | Title, Genres, Popularity, Vote Average |
| Target Variable  | Not applicable (Filtering-based system) |
| Input Features   | Genre, Popularity, Vote Average |
---

## 🛠️ Technologies & Libraries
- Python  
- Google Colab  
- Pandas  
- NumPy  
- ast (for genre processing)  

## 🔄 Project Workflow
### 1. Data Collection
Loaded the TMDB movie dataset from Kaggle.
### 2. Data Exploration
- Inspected dataset structure  
- Selected required columns  
- Understood genre format  
### 3. Data Preparation
- Extracted useful columns:
  - title  
  - genres  
  - popularity  
  - vote_average  
- Cleaned genre data using `ast.literal_eval()`
### 4. Recommendation System
Implemented basic filtering techniques:
- Genre-based recommendation  
- Top-rated movies filtering  
- Most popular movies filtering  
### 5. User Interaction
User inputs a genre and receives recommended movies.

## 📈 Results
The system successfully recommends movies based on genre, popularity, and rating using simple filtering techniques.

## 📂 Repository Contents
- Movie Recommendation System.ipynb  
- tmdb_5000_movies.csv  
- Project_Demo.mp4
- Screenshots: 
  dataset_loading.png
  data_cleaning_genres.png
  top_rated_movies.png
  popular_movies.png
  user_input_recommendation.png
- README.md  


## 🎥 Project Demo
👉https://drive.google.com/file/d/13rIHMxYDymANgk5Ql6GrPlLVEpnZO9n_/view?usp=sharing

## 🔗 Connect with Me
📌https://www.linkedin.com/posts/pallavi-sowreddi-421313368_horizonintern-machinelearning-python-ugcPost-7469797937951232001-GK6F/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFsry5kB2nChrqlIn88PU_V0-AGv5cZCQkQ

## 👩‍💻 Author
Pallavi Sowreddi  
Machine Learning Intern | Aspiring Data Scientist  

## 📜 Internship Information
This project was completed as part of the **Horizon Intern Machine Learning Internship Program**.
