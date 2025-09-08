# Deep Learning for Software Requirements Extraction

This repository contains a course project from **Software Requirements Engineering**, focusing on a **deep learning–based approach to automatically extract software requirement models from natural language problem descriptions**.

## Features

The project demonstrates:

- Preprocessing of raw requirement text (cleaning, tokenization, embedding).
- Use of neural networks to identify and classify requirement elements.
- Application of deep learning models (e.g., LSTM/GRU, CNN, or similar sequence models) to build structured requirement models.
- Evaluation of model performance on problem text descriptions.
- Exploration of how **NLP + deep learning** can support software requirements engineering.

---

### Notes & Limitations

- This was implemented as a class assignment — the dataset and experiments are limited in scale.
- The approach is a baseline exploration; production-level requirements engineering systems would need larger datasets and more sophisticated models.
- Demonstrates the promise of combining requirements engineering with modern deep learning NLP techniques.


### Required Libraries 
- spacy
- pytorch
- nltk
- transformers
- sci-kit learn
- torchvision

### Required Downloads
- nltk.download('punkt')
- spacy download en_core_web_sm
