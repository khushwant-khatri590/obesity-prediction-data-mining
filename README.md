# Estimating Obesity Levels Based on Eating Habits & Physical Condition

📊 A supervised and unsupervised data mining project using regression, classification, and clustering techniques to predict obesity levels based on eating habits, demographics, and physical activity data.

---

## 🧠 Objective

This project explores how lifestyle and physiological variables influence obesity levels, and builds predictive models to classify individuals into 7 distinct obesity categories using real-world data.

---

## 📚 Dataset

- **Source**: UCI Machine Learning Repository  
- **Dataset**: Estimation of Obesity Levels Based on Eating Habits and Physical Condition  
- **Records**: 2,111 individuals from Mexico, Peru, and Colombia  
- **Features**: 16 predictors (e.g., age, gender, meal frequency, water/alcohol intake, activity)  
- **Target**: Obesity level (7 classes: Insufficient, Normal, Overweight I/II, Obesity I/II/III)

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning: Logistic Regression, Decision Trees, Random Forest, SVM
- Clustering: K-Means, Hierarchical Clustering
- Preprocessing: StandardScaler, One-Hot Encoding

---

## 🔍 Methods Used

### 📈 Regression
- Predicted BMI using Linear Regression
- R² = 0.50, RMSE = 5.66  
- Key factors: Age, physical activity, water intake, meal frequency

### 📊 Classification
| Model               | Accuracy       |
|--------------------|----------------|
| Logistic Regression| 62.88% (→ 86.52% with height/weight) |
| Decision Tree       | 93.38%         |
| Random Forest       | **95.51%**     |
| SVM (Linear Kernel) | 93.85%         |

- Top features: Weight, Height, Age, Vegetable Intake, Physical Activity

### 🔗 Clustering
- K-Means & Hierarchical Clustering (k=5)
- Adjusted Rand Index (ARI): 0.19 (K-Means), 0.14 (Hierarchical)
- Revealed lifestyle-based groups even without labels

---

## 📁 Project Structure

obesity-prediction-data-mining/
├── CIS9660_Group7_Project.ipynb # Jupyter notebook with full code and analysis
├── CIS9660_Group7_Final_Report.pdf # Project report summarizing methods, results, and insights
├── CIS9660_Group7_Project_Proposal_Slides.pptx # Initial proposal presentatio
└── README.md # Project documentation


---

## 👥 Contributors

This project was completed for **CIS 9660 – Data Mining for Business Analytics**  
📍 Zicklin School of Business, Baruch College (Spring 2025)

**Group 7 – Team Members:**  
- Khushwant Khatri  
- Helly Harshad Shah  
- Vibha Gokhale  
- Maria Cristina Moreno Siguenza  
- Isha Thakkar  
- Khan Yunus

---

## 📌 Key Takeaways

- Tree-based models and linear SVM achieved over **93% accuracy**
- Lifestyle factors (snacking, physical activity) play a major role in predicting obesity
- Clustering uncovered meaningful health behavior patterns beyond labeled classes

---

## 📬 Contact

📧 khushwant.khatri03@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/khushwantkhatri)


