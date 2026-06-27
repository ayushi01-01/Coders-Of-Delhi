# Coders Of Delhi – Data Cleaning & Recommendation System of social network

## Project Overview
This project focuses on cleaning social network data and generating recommendations using Python.
The goal of this project is to clean social network data and generate intelligent recommendations and connect social network based on user interactions and interests.

This project simulates features commonly used in social media platforms such as:
- Data cleaning
- People You May Know
- Pages You Might Like

By applying data cleaning techniques and recommendation logic, the system provides meaningful suggestions to users.


## Features
- Data Cleaning and Structuring
- Remove duplicate records
- Remove inactive users
- People You May Know Recommendation
- Pages You Might Like Recommendation
- JSON Data Processing

## Tech Stack
- Python
- JSON
- Jupyter Notebook

## Project Workflow
1. Load Raw Data
2. Clean and Structure Data
3. Generate Friend Recommendations
4. Generate Page Suggestions

## Project Modules

 1. Data Cleaning
Performed preprocessing on raw dataset:
- Removed users with missing names
- Removed duplicate friend connections
- Removed duplicate pages
- Removed inactive users
- Created cleaned JSON dataset

Output:
cleaned_data2.json

2. People You May Know
Built a recommendation system to:
- Analyze user friend connections
- Find mutual friends
- Recommend new people

Logic Used:
Friend → Mutual Friend → Recommendation

Example Output:
User 1 → [4]

 3. Pages You Might Like
Built page recommendation functionality:
- Compared page interests
- Suggested pages users may prefer
- Ranked recommendations

Example Output:
User 1 → [102,104]


## Output
- Recommended People
- Suggested Pages
- Cleaned Dataset

## Learning Outcomes
Through this project I learned:
- Data preprocessing
- Recommendation system basics
- Python project structure
- Data preprocessing
- Working with JSON files
- Recommendation system basics
- Python project organization
- Data analysis workflow

---

## Future Improvements
- Add Machine Learning models
- Improve recommendation accuracy
- Build user interface
- Deploy as a web application
