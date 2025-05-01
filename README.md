# Multimodal-Sentiment-Analysis
Combines facial expression and text sentiment analysis using weighted voting to predict overall emotion. Built with OpenCV, NLP, and deep learning.

This project performs sentiment analysis by combining two input types:  
**Text input** (analyzed using sentiment analysis)  
**Facial expression** (analyzed using expression detection from webcam images)

The final sentiment is decided using a **weighted voting system**:
- **Text sentiment** has 7 votes
- **Facial expression sentiment** has 3 votes

## About This Notebook

The main notebook: `Multimodal_Sentiment_Analysis.ipynb`  
It contains:
- Text-based sentiment analysis using pretrained models or NLP libraries 
- Facial expression detection using OpenCV and a trained facial expression model
- Final prediction using a weighted voting function


## How to Run

1. Clone or download this repository
2. Open the notebook in Jupyter or Google Colab
3. Install dependencies (if needed):

```bash
pip install opencv-python numpy tensorflow keras nltk

