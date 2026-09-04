# CampusHireLens 🎓
### Placement Readiness & Skill-Gap Prediction using Machine Learning

CampusHireLens is an educational machine-learning prototype that estimates a student's placement-readiness level as **Low, Medium, or High** using academic performance and employability-preparation features.

## 💡 Why this project?
Students often know their academic marks but do not know which placement skills need improvement. CampusHireLens combines **ML prediction + feature importance + personalized skill-gap recommendations** to turn student inputs into an actionable preparation plan.

## 🧠 Features Used
- CGPA
- Coding hours per week
- DSA problems practiced
- Number of projects
- Internship experience (months)
- Aptitude score
- Communication score
- Mock interviews completed

## 🔄 Machine Learning Workflow
**Problem Definition → Data Generation → EDA → Preprocessing → Train/Test Split → Random Forest Classification → Evaluation → Feature Importance → Personalized Recommendations**

## 🛠️ Tech Stack
**Python | Pandas | NumPy | Matplotlib | scikit-learn | Jupyter/Google Colab**

## 📊 Model Result
Using a Random Forest classifier with class balancing on the educational dataset:

- Test accuracy: **80%**
- Macro F1-score: **0.59**
- Most influential features in this run:
  1. CGPA
  2. Mock interviews
  3. Aptitude score
  4. Coding hours per week
  5. Communication score

> These results are specific to the generated learning dataset and should not be interpreted as real-world hiring accuracy.

## 🎯 Example Output
For a sample student profile, the system predicts a readiness level and generates improvement suggestions such as increasing coding practice, practicing DSA, building projects, improving aptitude/communication, or completing mock interviews.

## 📁 Repository Contents
- `CampusHireLens.ipynb` — complete executable notebook
- `README.md` — project documentation
- `requirements.txt` — Python dependencies

## ▶️ How to Run
1. Open `CampusHireLens.ipynb` in Google Colab or Jupyter Notebook.
2. Run the cells from top to bottom.
3. Review the EDA charts, model metrics, feature importance, and personalized recommendation output.

## 🚀 Future Enhancements
- Use an ethically collected real-world placement dataset.
- Compare Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
- Add cross-validation and hyperparameter tuning.
- Build an interactive Streamlit dashboard.
- Add SHAP-based explanations for individual predictions.
- Add a downloadable student readiness report.

## ⚠️ Disclaimer
The current dataset is **synthetically generated for educational purposes**. CampusHireLens is a learning prototype and should not be used to make real hiring, admissions, or placement decisions.

## 👩‍💻 Author
**Sravani Katta**
