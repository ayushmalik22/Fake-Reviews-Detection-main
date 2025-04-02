# Fake Review Detection using AI & ML

## Overview
This project is designed to detect fake reviews using Machine Learning techniques. It utilizes Natural Language Processing (NLP) to analyze review text, detect anomalies, and classify reviews as legitimate or fraudulent.

## Features
- **Text Preprocessing**: Cleans review text by removing noise, correcting spelling, and applying stemming.
- **Machine Learning Classification**: Uses Logistic Regression with Count Vectorizer to classify reviews.
- **User Interface**: Built with Streamlit for easy interaction.
- **Performance Metrics**: Model achieves an accuracy of 85%, recall of 92%, and F1-score of 85%.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: Streamlit, NLTK, TextBlob, Pandas, NumPy, Scikit-learn, Pickle
- **Dataset**: Amazon Reviews Dataset ([Kaggle](https://www.kaggle.com/akudnaver/amazon-reviews-dataset))
- **Model**: Logistic Regression

## Installation
1. Clone the repository:
   ```sh
   git clone (https://github.com/ayushmalik22/Fake-Reviews-Detection-main.git)
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   streamlit run app.py
   ```

## Dataset
The model is trained using Amazon’s labeled dataset, which categorizes reviews as verified or non-verified purchases.

## Model Training
1. **Data Preprocessing**:
   - Stopword removal, stemming (PorterStemmer), and spelling correction (TextBlob).
2. **Feature Extraction**:
   - Count Vectorizer for converting text into numerical format.
3. **Training & Evaluation**:
   - Logistic Regression classifier trained with 60-40% train-test split.
   - Model achieves **85% accuracy, 80% precision, and 92% recall**.

## Usage
- Enter a review in the Streamlit UI.
- Click "Check" to classify whether the review is genuine or fake.
- Model processes the input and provides results with a probability score.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

## Contact
For queries, reach out via email at your- am24wde@gmail.com or open an issue in the repository.

