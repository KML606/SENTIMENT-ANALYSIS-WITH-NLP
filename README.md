# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: KAMAL SAHU

*INTERN ID*: CT04DH499

*DOMAIN*: MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR*: NEELA SANTOSH

Description:
In this project, the objective was to analyze the sentiment of customer reviews by building a machine learning model that classifies each review as either positive or negative. The task was carried out using Python in a Jupyter Notebook environment, with TF-IDF vectorization used to convert the text data into numerical form and Logistic Regression as the classification algorithm. Development and testing were performed using Visual Studio Code (VS Code), which provided an efficient interface for working with Jupyter Notebooks and Python scripts.

The dataset consisted of customer reviews labeled with their respective sentiments. The first step in the process was to import the necessary Python libraries such as pandas, numpy, scikit-learn, matplotlib, and seaborn. These were used for data manipulation, model training, and evaluation.

Once the data was loaded, a few initial checks were performed to understand its structure and class distribution. The core feature used in the model was the review text, and the label was the sentiment, which was later converted into binary values (1 for positive, 0 for negative).

Before feeding the text data into the model, a text preprocessing function was applied to clean the reviews. This function removed unnecessary characters such as punctuation, numbers, HTML tags, URLs, and converted all text to lowercase. This step was essential to ensure that the model focuses on meaningful content rather than noise.

The cleaned dataset was then split into training and testing sets using an 80:20 ratio. This allows the model to learn from one part of the data and be evaluated on another part it has never seen before. Following the split, the TF-IDF (Term Frequency–Inverse Document Frequency) vectorizer was used to convert the text into a matrix of features. This approach helps give more importance to unique and relevant words while downplaying commonly used ones.

Next, a Logistic Regression model was trained on the TF-IDF-transformed training data. After training, predictions were made on the test set and evaluated using metrics such as accuracy, precision, recall, and the confusion matrix. These metrics provided insight into how well the model was performing in distinguishing between positive and negative sentiments.

A confusion matrix was visualized using Seaborn’s heatmap to better understand the distribution of correct and incorrect predictions. Additionally, a few sample reviews were tested to demonstrate how the model would classify unseen input.

Overall, the project provided a complete pipeline for sentiment analysis—starting from preprocessing raw text, through vectorization, training, and evaluation. The use of VS Code made the development process seamless, especially with its support for extensions like Jupyter and Python linting.

This task successfully demonstrated a basic yet effective approach to natural language processing using traditional machine learning techniques. The final output is a clean and well-documented Jupyter Notebook that showcases the full workflow of a sentiment analysis model.

# OUTPUT

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/cd7f9179-91a6-4420-8fab-a3f540566017" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/61452725-9dd2-4aa6-8186-bfb927c76722" />

<img width="780" height="270" alt="Image" src="https://github.com/user-attachments/assets/60179e54-eb91-4d14-a21b-cca64eb3ff0a" />

<img width="672" height="303" alt="Image" src="https://github.com/user-attachments/assets/a2470487-c6a4-4765-8fb6-2ad34b414fad" />

<img width="766" height="689" alt="Image" src="https://github.com/user-attachments/assets/512e3ec1-0514-4cc4-be41-e1f4c1db0ef4" />

<img width="914" height="152" alt="Image" src="https://github.com/user-attachments/assets/1161fd80-746d-4131-9dcd-8b93164225a9" />

