# 📰 Fake News Prediction using Machine Learning

## 📘 About the Project
This project predicts whether a news article is **real or fake** using **Machine Learning**.  
The model is trained using the **Logistic Regression algorithm**.

---

## 🧩 Steps Involved

### 1. About the Dataset
The dataset contains news articles with columns like:
- `author`
- `title`
- `text`
- `label` (0 = Real, 1 = Fake)

---

### 2. Importing the Dependencies
We used Python libraries like:
- **NumPy**
- **Pandas**
- **scikit-learn**

---

### 3. Data Collection and Data Processing
The dataset is loaded and cleaned using Pandas.  
Missing values are handled and text data is combined for better analysis.

#### 3.1 Stemming
Stemming is the process of reducing words to their root form.  
Example:  
`actor, actress, acting → act`

This helps in improving text understanding for the model.

---

### 4. Splitting the Data
The dataset is divided into:
- **Training Data (80%)**
- **Testing Data (20%)**

---

### 5. Model Training
We trained the data using the **Logistic Regression** algorithm to detect fake news.

---

### 6. Model Evaluation
The model’s accuracy is checked using the **accuracy_score** function from scikit-learn.

---

### 7. Making a Predictive System
Finally, a system is built that takes news content as input and predicts whether it is **Real or Fake**.

---

## 🧠 Technologies Used
- Python  
- NumPy  
- Pandas  
- scikit-learn  
- Google Colab / Jupyter Notebook

---

## 📊 Result
The model successfully predicts fake and real news with good accuracy.

---

**Aditya Chauhan**
