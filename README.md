# SMS Spam Detection

This project was developed during my machine learning internship at CodSoft. It aims to identify whether a given SMS message is spam or ham (legitimate) using natural language processing and supervised learning models.

---

## Objective

To categorize SMS messages based on their content into two groups:  
- Spam (Unwanted messages)  
- Ham (Legitimate messages)  

---

## Dataset

The dataset has labeled SMS messages:  
- Columns:  
  - `label` - spam or ham  
  - `message` - text content of the SMS  
- Size: ~5,500 rows  

Source: Public UCI dataset often used for text classification

---

## Tech Stack

- Python  
- Jupyter Notebook  
- scikit-learn  
- pandas, NumPy  
- TF-IDF Vectorizer (for feature extraction)  
- Multinomial Naive Bayes (for classification)  

---

## Workflow

1. Data Preprocessing  
   - Cleaned and renamed columns, and encoded labels  

2. Text Vectorization  
   - Used TF-IDF to convert messages into numerical format  

3. Model Training  
   - Applied Multinomial Naive Bayes for spam detection  

4. Evaluation  
   - Checked accuracy, confusion matrix, and classification report  

5. Prediction  
   - Created a function to test new SMS messages

## Model Accuracy 
Accuracy over validation set: 96.23%

---

## Results

Achieved high accuracy with good performance on real-world messages. The model detects spam with great precision while using minimal resources.

---

## Usage

```bash
git clone https://github.com/itscherry06/CODSOFT.git
cd sms-spam-detection
```

##  Made by Cherry 🍒

> Engineering student. Dreaming entrepreneur. Machine learning fanatic.
> Made with ✨love, code, and chaos✨ during the CodSoft internship.

Let’s connect!  
📫 [LinkedIn]( www.linkedin.com/in/sai-charan-neerudu)  
📧 [Email]( mailto:neerudusaicharan042@gmail.com)
