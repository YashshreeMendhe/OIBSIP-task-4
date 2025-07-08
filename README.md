# OIBSIP-task-4
Twitter Sentiment Analysis using Machine Learning 
# Task 4 - Sentiment Analysis 📊🧠

## 📌 Objective:
To perform sentiment analysis on Twitter data using Machine Learning techniques.

---

## 📁 Dataset:
- **File:** `Twitter_Data.csv`
- **Shape:** 162,980 rows × 2 columns
- **Columns:**
  - `clean_text`: Cleaned tweets
  - `category`: Sentiment label (0 = Negative, 1 = Positive, 2 = Neutral)

---

## 🧠 Techniques Used:

1. Data Preprocessing (handling nulls, cleaning)
2. Text Vectorization using **TF-IDF**
3. Machine Learning model: **Multinomial Naive Bayes**
4. Evaluation using Accuracy, Precision, Recall, F1-Score
5. Output: Sentiment prediction on test data

---

## 🔍 Files Included:

| File                        | Description                             |
|-----------------------------|-----------------------------------------|
| `Twitter_Data.csv`          | Original tweet dataset                  |
| `Task_4_Sentiment_Analysis.ipynb` | Jupyter Notebook with code and visuals |
| `Sentiment_Predictions.csv` | Model predictions on test set           |
| `README.md`                 | Project summary                         |

---

## 📊 Sample Output

```csv
Actual,Predicted
1.0,1.0
0.0,0.0
2.0,2.0
...

