# spam-mail-detection


The following steps were followed in this project:

1. **Data Loading & Exploration**
   - Loaded the spam email dataset
   - Analyzed class distribution

2. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Removal of stopwords and punctuation
   - Stemming

3. **Handling Class Imbalance**
   - The dataset was highly imbalanced
   - Balanced by downsampling the majority class (ham)

4. **Feature Extraction**
   - TF-IDF Vectorization

5. **Model Training**
   - Multinomial Naive Bayes classifier

6. **Evaluation**
   - Confusion matrix
   - Classification report

7. **Prediction**
   - Custom function to classify new email text
