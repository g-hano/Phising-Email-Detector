# Email Classification

This project is a Python-based email classification system that uses machine learning techniques to classify emails as either safe or phishing emails.

## Description

The purpose of this project is to preprocess and analyze email data using various libraries and tools in Python. The project utilizes the following key components:

- **Pandas:** Used for data preprocessing tasks such as data cleaning and exploration.
- **Spacy:** Used for handling stop words in the text data.
- **NLTK (Natural Language Toolkit):** Used for stemming using the PorterStemmer algorithm.
- **Scikit-learn:** Utilized the `train_test_split` function to split the dataset into training and testing sets.
- **TensorFlow and Keras:** Used to build and train the machine learning model.
    - The model architecture consists of an embedding layer, LSTM layer, and dense layer with sigmoid activation.
    - The model is compiled with the 'adam' optimizer.
    
The dataset used in this project contains approximately 18,000 rows of email data, but for the purpose of training and evaluation, the first 10,000 rows were used. The trained model achieved an accuracy of 87% on the training set and 88% on the test set.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/g-hano/Phising-Email-Detector.git
   ```

2. Install the required dependencies:
   ```shell
   pip install pandas spacy nltk tensorflow scikit-learn
   ```

3. Download the necessary language models for Spacy:
   ```shell
   python -m spacy download en
   ```

4. Run the Python script:
   ```shell
   python DataCleaning_and_Model.py
   ```

## Usage

Once the project is set up and the Python script is executed, the system will read email data and classify each email as either safe or phishing. The classification results will be displayed or saved for further analysis.

## Contributing

Contributions to this project are welcome. If you have any suggestions, enhancements, or bug fixes, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank the developers of the libraries and tools used in this project, as well as the creators of the dataset used for training and evaluation.

## Contact

For any inquiries or questions, feel free to reach out to the project maintainer at [mcihann19@hotmail.com](mailto:mcihann19@hotmail.com).
