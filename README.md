# Deep Sentiment Analysis  

This project implements **Deep Sentiment Analysis** using a Recurrent Neural Network (RNN) and Word Embeddings. The goal is to predict whether a movie review expresses a positive or negative sentiment. The project uses the IMDB movie review dataset, which contains 50,000 labeled reviews split equally between positive and negative sentiments.  

---

## Features  

- **Dataset**: IMDB movie review dataset with 50,000 samples.  
- **Deep Learning Pipeline**:  
  - Use Keras's Embedding Layer to create word embeddings.  
  - Prepare and preprocess the dataset for NLP tasks.  
  - Train an RNN model for sentiment classification.  
- **Visualization**: Plot model training metrics such as accuracy and loss.  

---

## Installation  

### Clone the Repository  

```bash
git clone https://github.com/your-username/deep-sentiment-analysis.git  
cd deep-sentiment-analysis  
```

## Install Dependencies
Ensure you have Python 3.7+ and the required libraries installed:

```bash
pip install -r requirements.txt
```
## How to Run
1. Open the notebook:
``` bash
jupyter notebook qa_rag_climate_fever.ipynb
```
or use google colab 

2. Follow the steps in the notebook to:

  - Load and preprocess the dataset.
  - Build the RNN model.
  - Train and evaluate the model.
  - Visualize training metrics.

## Dependencies
- numpy
- pandas
- matplotlib
- nltk
- tensorflow

Install them using the requirements.txt file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The IMDB dataset is widely used for sentiment analysis benchmarks.
= This project utilizes TensorFlow and Keras for deep learning tasks.
