# SPAMDETECTION
This idea is to detect the spam message using ML techniques
# Steps Followed
1. **Data Preprocessing**:
   - Converted all text to lowercase for uniformity.
   - Removed numbers and special characters using regular expressions.
   - Cleaned the text to remove unwanted tokens and words.

2. **Feature Extraction**:
   - Used the **TF-IDF Vectorizer** to convert the raw SMS messages into numerical vectors that can be fed into a machine learning model.

3. **Model Building**:
   - Trained a **Multinomial Naive Bayes (MNB)** model for classification.
   - Applied **GridSearchCV** for hyperparameter tuning to find the best settings for the model.

4. **Model Evaluation**:
   - Evaluated the model using various metrics like **accuracy**, **precision**, **recall**, and **F1-score**.
   - The model achieved a high accuracy of **X.XX%**, indicating good performance in distinguishing between spam and non-spam messages.

## Key Insights
- **Text Preprocessing** and **Feature Extraction** play crucial roles in improving the model's performance.
- The **Multinomial Naive Bayes** classifier is particularly effective for text classification tasks due to its simplicity and efficiency in handling large datasets.

# Dataset
The dataset used for this project is the **SMS Spam Collection Dataset** from Kaggle.(https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

# How to Run:
1. Clone this repository.
2. Install required dependencies from `requirements.txt`.
3. Run the notebook to train the model and evaluate its performance.

## Future Improvements
- **Advanced Feature Engineering**: Exploring other NLP techniques like word embeddings or deep learning models for better performance.
- **Model Optimization**: Experimenting with different machine learning algorithms like **Random Forest**, **SVM**, or **Logistic Regression** to improve classification results.
- **Handling Imbalanced Data**: Implementing techniques like **SMOTE** to handle any class imbalance in the dataset.


**#Author:**
Priyadharshini V
