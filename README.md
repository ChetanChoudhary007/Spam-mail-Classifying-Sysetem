# Spam Mail Classifying System

![Spam Mail Classifier](https://miro.medium.com/v2/resize:fit:470/1*byZ8tSrUasgfCvHU0a315Q.png)


This project is a simple spam mail classifier that uses a logistic regression model to classify emails as spam or ham (non-spam). It leverages the scikit-learn library for data preprocessing, feature extraction, model training, and testing.

## Getting Started

To use this project, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spam-mail-classifier.git
   ```

2. Install the required dependencies:

   ```bash
   pip install pandas scikit-learn
   ```

3. Run the main script:

   ```bash
   python spam_mail_classifier.py
   ```

## Project Structure

- `spam_mail_classifier.py`: The main script containing the entire code for loading data, preprocessing, feature extraction, model training, and testing.
- `mail_data.csv`: The dataset containing email messages and their corresponding categories (spam/ham).

## Usage

1. **Loading and Preprocessing Data**: The script loads the dataset from `mail_data.csv`, handles null values, and encodes labels as 0 for ham and 1 for spam.

2. **Splitting Data**: The dataset is split into training and testing sets using `train_test_split` from scikit-learn.

3. **Feature Extraction**: Text data is transformed into feature vectors using `TfidfVectorizer`, which converts text into numerical features suitable for the logistic regression model.

4. **Model Training**: The logistic regression model is trained using the training data.

5. **Model Testing**: The accuracy of the model is evaluated on the testing data.

6. **Spam E-mail Classifying System**: The user can input an email message, which is then converted into a feature vector. The trained model predicts whether the input email is spam or ham.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to create a pull request.

## License
