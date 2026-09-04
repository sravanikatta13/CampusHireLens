# CampusHireLens 🎓 — Placement Readiness & Skill-Gap Prediction

CampusHireLens is an educational machine learning project that predicts a student's placement-readiness level (Low, Medium, or High) from academic performance and employability-preparation features.

## Why this project?
Many students know their grades but do not know which placement skills to improve. CampusHireLens combines an ML classifier with a simple personalized skill-gap analyzer.

## Features
- CGPA
- Coding hours per week
- Number of DSA problems practiced
- Number of projects
- Internship experience in months
- Aptitude score
- Communication score
- Number of mock interviews

## Machine Learning Workflow
1. Generate a self-contained learning dataset
2. Explore readiness patterns
3. Split data into training and testing sets
4. Standardize numerical features
5. Train a Random Forest classifier
6. Evaluate accuracy and classification metrics
7. Analyze feature importance
8. Generate personalized improvement suggestions

## Tech Stack
Python • Pandas • NumPy • Matplotlib • scikit-learn • Jupyter/Google Colab

## Run
Open `CampusHireLens.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom.

## Project Note
The dataset is synthetically generated for educational purposes. The project is a prototype and is not intended to make real hiring or placement decisions.

## Future Scope
A future version can use an ethically collected real-world dataset, compare multiple models, add cross-validation, and provide a Streamlit dashboard.
