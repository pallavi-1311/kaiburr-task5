# Kaiburr Assessment – Task 5  
### Candidate: Pallavi Kasam  

---

## Objective
Perform **Text Classification** on the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)  
to classify complaints into the following 4 categories:

| Label | Category |
|--------|-----------|
| 0 | Credit reporting, repair, or other |
| 1 | Debt collection |
| 2 | Consumer Loan |
| 3 | Mortgage |

---

## Tech Stack
- **Python 3**
- **Pandas**, **NumPy**
- **Scikit-Learn**
- **NLTK**
- **Matplotlib**, **Seaborn**, **WordCloud**
- **Jupyter Notebook (VS Code)**

---

## Steps Performed
1. Loaded dataset from the Consumer Complaint Database  
2. Filtered relevant product categories  
3. Cleaned text (lowercased + removed stopwords)  
4. Converted text → TF-IDF features  
5. Trained models: Naive Bayes and Logistic Regression  
6. Compared accuracy and classification reports  
7. Visualized results using word cloud and confusion matrix  

---

## Results

| Model | Accuracy |
|--------|-----------|
| Naive Bayes | **0.95** |
| Logistic Regression | **0.967** |

**Logistic Regression** achieved the best overall performance.  


