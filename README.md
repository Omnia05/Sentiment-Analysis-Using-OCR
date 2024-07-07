# Sentiment Analysis Using OCR

Sentiment Analysis of Handwritten Text Using Custom-built OCR and Sentiment Classification Models

## Background

The analysis of handwritten text for sentiment involves two main tasks: recognizing the text content (Optical Character Recognition, OCR) and determining the sentiment conveyed by the text (Sentiment Analysis). Unlike printed text, handwritten text poses significant challenges due to variations in writing styles and inconsistencies. The absence of pre-trained models necessitates the creation of custom solutions for both OCR and sentiment analysis.

### OCR (Optical Character Recognition)

OCR is a Computer Vision (CV) foundational technology behind the conversion of typed, handwritten or printed text from images into machine-encoded text.

### Sentiment Analysis

Sentiment analysis is a Natural Language Processing (NLP) technique of analyzing text to determine if the emotional tone of the message is positive, negative, or neutral. 

## Project Description

The primary objective of this project is to use artificial intelligence to convert handwritten text images into digital text and subsequently perform sentiment analysis ( using just basic word count and Naive Bayes method ) on the extracted text. The project will leverage the provided labelled dataset of handwritten alphabets (alphabets_28x28.csv) in the form of pixel data, the sentiment analysis dataset (sentiment_analysis_dataset.csv) and the target labels dataset (target_labels.csv). Finally, the performance is to be tested and reported on the images provided in the target_images folder.

### Results

The OCR Model's accuracy is shown.  
The Sentiment Analysis Model's accuracy is shown along with it's results for the images in the target_images folder.  

## Prerequisites

Make sure to have pandas, numpy, tensorflow and scikit installed on your system.  
If not already installed, run these commands on your terminal:  
1. pip install pandas  
2. pip install numpy
3. pip install tensorflow  
4. pip install scikit-learn

## Resources

Going through the NumPy, TensorFlow and Scikit-learn documentation has proven to be very useful.  
Sites like GeeksforGeeks provided a lot conceptual explanations.  
Stanford documentation for Naive Bayes: https://web.stanford.edu/~jurafsky/slp3/4.pdf  
Video Reference for the OCR Model: https://youtu.be/bte8Er0QhDg?si=kzjA7wRJEdJFfzsB  
Layout Reference: https://github.com/anmolsaluja28/OCR-and-Sentiment-Analysis-of-Quotes/blob/main/Code.ipynb  

## Note

This is my first attempt at building an OCR Model and a Sentiment Analysis Model. As a newcomer to these topics, I found this project both fun and insightful. It gave me an oppurtunity to explore concepts related to CV & NLP and thier integration.  

So far, my OCR Model seems to be working fine with an accuracy ~96.5%. But, there seems to be an issue in the sentiment analysis part, resulting to an accuracy ~67%.  
I hope to fix these issues, so my model works more accurately. Any suggestions are always welcome.




