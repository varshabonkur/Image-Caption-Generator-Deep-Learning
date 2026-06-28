# Image Caption Generator Using Deep Learning

## Overview

This project generates meaningful captions for images using Deep Learning by combining Computer Vision and Natural Language Processing techniques.

The model follows an Encoder–Decoder architecture:

* Encoder: InceptionV3 (CNN) for image feature extraction
* Decoder: LSTM for natural language caption generation

## Features

* Image preprocessing
* Feature extraction using InceptionV3
* Caption preprocessing and tokenization
* CNN–LSTM architecture
* Automatic caption generation
* BLEU score evaluation

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* NLTK
* Google Colab

## Dataset

Dataset: Flickr8k

* 8,092 images
* 5 captions per image
* Approximately 40,000 captions

## Project Structure

```
Image-Caption-Generator-Deep-Learning/
│
├── README.md
├── requirements.txt
├── Image_Caption_Generator.ipynb
├── Abstract.docx
├── Algorithm.docx
├── images/
├── model/
├── outputs/
└── dataset/
```

## Workflow

1. Load Flickr8k Dataset
2. Preprocess Captions
3. Extract Image Features
4. Tokenize Captions
5. Train CNN-LSTM Model
6. Generate Captions
7. Evaluate using BLEU Score

## Future Improvements

* Attention Mechanism
* Transformer-based Captioning
* Beam Search
* Multilingual Caption Generation

## Author

Varsha Bonkur
