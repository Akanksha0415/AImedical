# AI Medical Diagnosis App

A Flask-based web application that predicts possible diseases based on user-entered symptoms using a machine learning model.

## Features

- Predicts disease from symptoms
- Simple web-based interface
- Uses a trained machine learning model
- Displays prediction results instantly
- Includes additional pages like About, Contact, Blog, and Developer

## Tech Stack

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML/CSS

## Project Structure

```bash
AI-Medical-Diagnosis/
│
├── datasets/
│   ├── symptoms_df.csv
│   ├── precautions_df.csv
│   ├── workout_df.csv
│   ├── description.csv
│   ├── medications.csv
│   └── diets.csv
│
├── models/
│   └── svc.pkl
│
├── static/
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── blog.html
│   └── developer.html
│
├── main.py
└── README.md
