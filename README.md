# 🎓 CS Students Track Recommendation System

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Matplotlib%20%7C%20Seaborn-lightgrey)]()
[![ML](https://img.shields.io/badge/ML-ScikitLearn-orange?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Models](https://img.shields.io/badge/Models-RF%20%7C%20SVM%20%7C%20GB%20%7C%20KNN%20%7C%20LR-yellow)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()
[![Visualization](https://img.shields.io/badge/EDA-Matplotlib%20%26%20Seaborn-blueviolet)]()
[![Encoding](https://img.shields.io/badge/Feature%20Encoding-LabelEncoder-lightgrey)]()
[![Saved%20Model](https://img.shields.io/badge/Export-Pickle-success)]()

**Career Track Recommendation Model**

An intelligent Machine Learning project designed to recommend the most suitable **career track** for Computer Science students based on their **skills, interests, GPA, and background**.

The system processes and visualizes student data, encodes features, trains multiple models (Random Forest, SVM, Gradient Boosting, etc.), compares their performance, and saves the best-performing model for deployment.

---

## 🚀 Features

✅ Automated data preprocessing and encoding
📊 Comprehensive EDA and data visualization (Track, Skills, GPA, Gender, etc.)
🧠 Multi-model training (Random Forest, SVM, Gradient Boosting, KNN, Logistic Regression)
📈 Model comparison and accuracy ranking
💾 Model saving (with scaler and encoders for later use)
🧮 Correlation analysis for feature importance insight
🎯 Sample prediction results for model validation

---

## 📂 Folder Structure

```
Path2Grad--Track-Recommendation--Model/
├── .gitignore                       # Ignore IDE and data-related temporary files
├── LICENSE                          # MIT License information
├── README.md                        # Project documentation 
├── SurveyModel.ipynb                # Main Jupyter Notebook 
└── requirements.txt                 # Python dependencies

```

---

## 🧠 Tech Stack

**Language:** Python (3.12)
**Libraries:**
`Pandas · NumPy · Scikit-learn · Seaborn · Matplotlib`

**Machine Learning Models:**

* Random Forest
* Support Vector Machine (SVM)
* Gradient Boosting
* K-Nearest Neighbors (KNN)
* Logistic Regression

---

## ⚙️ Installation & Setup

1️⃣ **Clone the repository:**

```bash
git clone https://github.com/safiasaad2/Path2Grad----Track-Recommendation--Model.git
cd Path2Grad----Track-Recommendation--Model
```

2️⃣ **Install dependencies:**

```bash
pip install -r requirements.txt
```

3️⃣ Run the main notebook:

jupyter notebook SurveyModel.ipynb


All visualizations and results will be saved automatically in the project folder.

## 📊 Dataset

**Dataset name:** `cs_students1.csv`
This dataset includes:

* 🎯 Student demographics (Age, Gender, GPA)
* 💻 Technical skills (Python, Java, SQL)
* 🌐 Interested Domain
* 🧩 Target variable: **Track** (the student’s career path)

---

## 📈 Model Performance

| Model                  | Accuracy | Precision | Recall   | F1       | 
| ---------------------- | -------- | --------- | -------- | -------- | 
| Logistic Regression    | 0.58     | 0.36      | 0.41     | 0.35     |
| K-Nearest Neighbors    | 0.56     | 0.40      | 0.48     | 0.39     |
| Support Vector Machine | 0.67     | 0.48      | 0.50     | 0.47     |
| Random Forest          | 0.83     | 0.62      | 0.74     | 0.66     |
| Gradient Boosting      | **0.92** | **0.70**  | **0.72** | **0.71** |

---


✅ **Best Model:** Gradient Boosting
✅ **Accuracy:** ~92%

---

## 🧩 Visualizations

* **Track Distribution** (Top 15 Tracks)
* **Gender Distribution**
* **GPA and Age Distributions**
* **Interested Domain Popularity**
* **Skill Strength (Python, SQL, Java)**
* **Track Distribution by Gender**
* **Feature Correlation Heatmap**
* **Model Performance Comparison**

---

## 💾 Saved Artifacts

After training, the following files are generated automatically:

* `track_recommendation_model.pkl` → Best model
* `scaler.pkl` → StandardScaler used in preprocessing
* `track_encoder.pkl` → Label encoder for Track
* `label_encoders.pkl` → Label encoders for categorical features

These can be loaded later for deployment or further predictions.

---

## 🧪 Sample Output

```
Sample Predictions vs Actual:
------------------------------------------------------------
1. Predicted: AI Engineering              | Actual: AI Engineering              ✓
2. Predicted: Data Science                | Actual: Data Science                ✓
3. Predicted: Cybersecurity               | Actual: Cloud Computing             ✗
4. Predicted: Software Development        | Actual: Software Development        ✓
5. Predicted: Game Development            | Actual: Game Development            ✓
```

## 👩‍💻 Author

**Safia Saad**
🎓 AI Engineer| Passionate about AI
📧 [safiakotb123@gmail.com](mailto:safiakotb123@gmail.com)

---

## 🪪 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with proper attribution.

⭐ **If you find this helpful, give it a star on GitHub!**

---
؟
