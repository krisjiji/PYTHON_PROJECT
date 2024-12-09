Student Lifestyle Analysis
Project Overview

This project involves a thorough examination of lifestyle data from students. It includes:

- Gathering information and keeping it in a SQLite database.

- A web application built with Flask is used to serve the data.

- Using dynamically produced web pages to display the data.

* This project's main objective is to use interactive and user-friendly web sites to offer insights about the habits, performance, and general well-being of students.

Features

1. Data Collection

- The dataset captures key aspects of student lifestyles, such as study hours, sleep patterns, and stress levels.

- The data is stored in a SQLite database for efficient retrieval.

2. Database Integration

- Utilizes SQLite for storing and managing the dataset.

- Data is stored in a single table, with fields like Student_ID, Study_Hours_Per_Day, GPA, and Stress_Level.

3. Flask Web Application

- Home Page: Provides an introduction to the project.

- About Data Page: Source, including definitions of each variable.

- Data Page: Displays a table with data from the SQLite database.

- Team page : Get to know the amazing individuals who make up our team.

How to Run

Prerequisites

- Python 3.x installed on your system.

- Required Python packages (listed in requirements.txt).

Steps

1. Clone the GitHub repository.

2. Navigate to the project directory.

3. Install the necessary packages:
    - pip install -r requirements.txt

4. Run the Flask application:
    -  python app.py

Open your browser and navigate to:

- http://127.0.0.1:5000/ for the home page.

- http://127.0.0.1:5000/about for the about page.

- http://127.0.0.1:5000/data for the data page.

Python_Project/
|-- static/
|   -- images/
|       |-- bg,jpg
|       |-- bg3.jpg
|       |-- chris.jpg
|       |-- jincy.jpg
|       |-- madhav.jpg
|       |-- rishav.jpg
|   |-- styles.css
|-- templates/
|   |-- home.html
|   |-- about.html
|   |-- data.html
|   |-- team.html
|-- app.py
|-- database_con.ipyb
|-- Student_lifestyle.db
|-- student_lifestyle_dataset.csv
|-- README.md
|-- requirements.txt

Dataset Details

Source: https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset

Variables:

Study_Hours_Per_Day: Average hours spent studying daily.

Extracurricular_Hours_Per_Day: Hours spent on extracurricular activities daily.

Sleep_Hours_Per_Day: Average hours of sleep daily.

Social_Hours_Per_Day: Hours spent socializing daily.

Physical_Activity_Hours_Per_Day: Hours spent on physical activities daily.

GPA: Student's Grade Point Average.

Stress_Level: Stress level categorized as Low, Moderate, or High.

If you dont have the requirement specified :  
- pip freeze > requirements.txt

