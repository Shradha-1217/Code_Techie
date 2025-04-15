
## 📧 Spam Detection using Machine Learning

This project focuses on building a spam detection system using machine learning techniques. By training a model on a labeled dataset of SMS messages, it can effectively classify incoming texts as **spam** or **ham (not spam)**.

### 📂 Project Structure

- `HW(1).ipynb`: Main Jupyter Notebook with data preprocessing, visualization, model training, and evaluation.
- `spam_ham_dataset.csv`: Dataset containing SMS messages labeled as spam or ham.

### 📊 Dataset Overview

The dataset includes the following features:

- `label`: Indicates whether the message is `spam` or `ham`.
- `text`: The content of the message.
- `label_num`: Numerical representation of the label (`0` = ham, `1` = spam).

### 🛠️ Technologies Used

- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and building ML models

### ✅ Steps Performed

1. **Data Loading**  
   Loaded and explored the SMS spam dataset.

2. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Converted labels to numerical format  
   - Tokenized and vectorized text data using `CountVectorizer`

3. **Model Training**  
   Trained a Naive Bayes classifier on the processed data.

4. **Model Evaluation**  
   Evaluated the model using accuracy score and classification report.

5. **Visualization**  
   Visualized data distribution and model performance.

### 📈 Results

- Achieved a high accuracy score (typically ~98%)
- Naive Bayes proved to be an effective model for text classification in this task

### 📌 How to Run

1. Clone the repo or download the files.
2. Make sure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the `HW(1).ipynb` notebook.

### 💡 Future Improvements

- Try other models like Logistic Regression, SVM, or ensemble methods
- Use TF-IDF instead of CountVectorizer for better feature representation
- Deploy the model as a web app

