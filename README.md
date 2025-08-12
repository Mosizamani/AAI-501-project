# Teen Smartphone Addiction Prediction

This project is part of the AAI-501 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

**Project Status:** Completed

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mosizamani/AAI-501-project/tree/main
   cd teen-smartphone-addiction
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook to explore the analysis and models:
   ```bash
   jupyter notebook teen_phone_addiction.ipynb
   ```

---

## Project Intro / Objective

The purpose of this project is to develop a machine learning system capable of classifying a teenager's risk of smartphone addiction as either high or low. The project aims to support the development of data-driven tools that can help educators, parents, and healthcare professionals identify early warning signs of problematic smartphone usage in adolescents. By combining supervised and unsupervised learning techniques, the project not only predicts addiction risk but also uncovers behavioral subgroups within the high-risk population.

---

## Contributors

- **Team Members:** Wael Sultan, Denis Mulabegovic and Mostafa Zamani Turk

---

## Methods Used

- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA)  
- Supervised Machine Learning (Logistic Regression, Decision Tree, Random Forest)  
- Unsupervised Learning (K-means Clustering)  
- Statistical Analysis (t-tests, correlation analysis)  
- Data Visualization (matplotlib, seaborn)

---

## Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Jupyter Notebook  
- Logistic Regression, Decision Tree, Random Forest  
- K-means Clustering


---

## Project Description

The dataset used contains 3,000 synthetic but statistically realistic adolescent profiles sourced from Kaggle. Each record includes demographic, behavioral, lifestyle, and mental health variables. The target variable, **Addiction_Binary**, classifies participants into high or low smartphone addiction categories based on their continuous addiction scores.

**Key Dataset Details:**
- **Source:** Kaggle synthetic teen smartphone addiction dataset  
- **Size:** 3,000 records  
- **Variables:** ~25 features covering phone usage behavior, sleep patterns, app usage diversity, mental health indicators, and academic performance  

**Exploratory Data Analysis Highlights:**
- High-addiction teens used their phones significantly more (average 6 hours/day) than low-addiction teens (3 hours/day) and checked their phones more frequently.
- Social media and app diversity were strong predictors of addiction.
- Sleep hours were negatively correlated with addiction level.
- Mental health and academic performance showed limited predictive power in isolation.

**Modeling Overview:**
- **Supervised Learning:** Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting models were tested. Key predictors such as daily usage hours, phone checks, apps used daily, and social media time consistently ranked high in feature importance.
- **Unsupervised Learning:** Clustering was performed within the high-addiction group to identify subgroups with similar behavior patterns.
- **Class Imbalance:** Addressed using Synthetic Minority Oversampling Technique (SMOTE).

---

## License

This project is licensed under the MIT License. 

---

## Acknowledgments

We thank professor Andrew Van Benschoten and the University of San Diego Applied Artificial Intelligence Program for their guidance and resources in completing this project.
