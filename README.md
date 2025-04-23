Objective:
The goal of this project is to classify text data from three different languages (English) as either "Spam" or "Ham" (not spam). Using a machine learning model, we aim to accurately classify the dataset based on text features.

Dataset:
The dataset consists of text messages labeled as "Spam" or "Ham" .

Workflow
1. Data Loading & Preprocessing
Load the dataset: Use Pandas to load the CSV file into a DataFrame.
Missing values: Check for missing values and clean or remove them as necessary.
Balancing the dataset: Ensure the dataset is balanced. If the dataset is imbalanced, apply techniques such as oversampling, undersampling, or using class weights in the model.
2. Feature Extraction
Vectorization: Use TfidfVectorizer to convert the text data into numerical representations. The vectorizer should handle multiple languages.
Language-agnostic vectorization: Ensure that the vectorization process works well across all languages (English, French, and German).
3. Model Training
Multinomial Naïve Bayes: Train a Multinomial Naïve Bayes model using the preprocessed text data. Understand the principles of MultinomialNB to better implement and tune the model.
4. Model Evaluation
Accuracy: Print the accuracy of the trained model.


![image](https://github.com/user-attachments/assets/b30f08dc-fa4c-40de-9961-e8f3e788f5ba)
![image](https://github.com/user-attachments/assets/a4dbe209-4979-4bc6-966c-48d3307608cf)
