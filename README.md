# 🤗 Hugging Face Transformers & Pipelines

A comprehensive hands-on repository demonstrating the use of **Hugging Face Transformers** and **Pipelines** for **Natural Language Processing (NLP)** and **Generative AI** tasks. This repository explores how to leverage pre-trained models from the Hugging Face Hub to perform various AI tasks without training models from scratch.

---

# 📖 Overview

This repository serves as a practical introduction to the Hugging Face ecosystem. It demonstrates how to authenticate with Hugging Face, load pre-trained models, and use the high-level **Pipeline API** to perform a wide range of NLP and Generative AI tasks.

Instead of building and training deep learning models, this project focuses on **inference** using powerful pre-trained models hosted on the Hugging Face Hub.

The repository includes practical examples covering:

- Hugging Face Authentication
- Transformers Library
- Pipeline API
- Sentiment Analysis
- Named Entity Recognition (NER)
- Question Answering
- Text Summarization
- Language Translation
- Zero-Shot Classification
- Text Generation
- Text-to-Image Generation
- Text-to-Speech Generation

---

# 🎯 Objectives

The main objectives of this repository are:

- Learn the fundamentals of Hugging Face Transformers.
- Understand the difference between training and inference.
- Learn how to authenticate using a Hugging Face Access Token.
- Explore the Hugging Face Pipeline API.
- Perform multiple NLP tasks using pre-trained models.
- Explore Generative AI capabilities such as image and speech generation.
- Understand how AI applications can be built with minimal code using pre-trained models.

---

# 🚀 Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Hugging Face Hub
- Diffusers
- PyTorch
- Stable Diffusion
- SpeechT5

---

# 📚 Topics Covered

## 1. Hugging Face Introduction

- Creating a Hugging Face account
- Generating an Access Token
- Using Google Colab Secrets
- Authenticating with Hugging Face

---

## 2. Transformers Library

Learned how the **Transformers** library provides access to thousands of pre-trained AI models for various NLP and Generative AI tasks.

---

## 3. Hugging Face Pipelines

Understood how pipelines simplify model usage by automatically handling:

- Model loading
- Tokenization
- Input preprocessing
- Inference
- Output formatting

---

# 🧠 NLP Pipelines

## ✅ Sentiment Analysis

Determines whether text expresses a positive or negative sentiment.

Example:

```
Input:
"I love this course."

Output:
Positive
```

---

## ✅ Named Entity Recognition (NER)

Extracts important entities from text such as:

- Person
- Organization
- Location
- Date
- Money

Example:

```
Input:
"Elon Musk founded SpaceX."

Output:
Person → Elon Musk
Organization → SpaceX
```

---

## ✅ Question Answering

Answers questions based on a provided context.

Example:

```
Context:
Python was created by Guido van Rossum.

Question:
Who created Python?

Answer:
Guido van Rossum
```

---

## ✅ Text Summarization

Converts long articles or paragraphs into concise summaries while preserving important information.

---

## ✅ Translation

Translated text between multiple languages.

Examples include:

- English → French
- English → Spanish

---

## ✅ Zero-Shot Classification

Classifies text using custom labels without additional model training.

Example:

```
Text:
"India won the cricket match."

Labels:

- Sports
- Politics
- Finance

Prediction:
Sports
```

---

# 🤖 Generative AI Pipelines

## ✅ Text Generation

Generated new text from a given prompt using pre-trained language models.

Example:

```
Prompt:
Once upon a time

Output:
Once upon a time there lived a brave knight...
```

---

## 🎨 Text-to-Image

Used **Stable Diffusion** to generate realistic images from text descriptions.

Workflow:

```
Text Prompt
      ↓
Stable Diffusion Model
      ↓
Generated Image
```

---

## 🔊 Text-to-Speech

Used **SpeechT5** to convert text into natural-sounding speech using pre-trained voice embeddings.

Workflow:

```
Input Text
      ↓
SpeechT5 Model
      ↓
Generated Audio
```

---

# 🏗️ Repository Structure

```
huggingface-transformers/
│
├── notebooks/
│   ├── practice1.ipynb
│   ├── practice2.ipynb

```

---

# ⚙️ Setup Instructions

### Clone Repository

```bash
git clone https://github.com/Khanapatro/HuggingFacePractice.git

cd HuggingFacePractice
```

---

### Install Dependencies

```bash
pip install transformers
pip install diffusers
pip install torch
pip install huggingface_hub
```

---

### Create Hugging Face Token

1. Create a Hugging Face account.
2. Generate an Access Token.
3. Store the token securely in **Google Colab Secrets** as:

```
HF_TOKEN
```

4. Authenticate before downloading models.

---

# 📊 Pipeline Tasks Covered

| Task | Description |
|------|-------------|
| Sentiment Analysis | Detect positive or negative sentiment |
| Named Entity Recognition | Identify people, organizations, and locations |
| Question Answering | Extract answers from a given context |
| Summarization | Generate concise summaries |
| Translation | Translate between languages |
| Zero-Shot Classification | Classify text using custom labels |
| Text Generation | Generate text from prompts |
| Text-to-Image | Generate images using Stable Diffusion |
| Text-to-Speech | Generate speech using SpeechT5 |

---

# 🎓 Learning Outcomes

After completing this repository, you will understand:

- Hugging Face ecosystem
- Transformers library
- Hugging Face Hub
- Pipeline API
- Authentication using Access Tokens
- Pre-trained AI models
- NLP inference workflows
- Generative AI applications
- Image generation using Stable Diffusion
- Speech generation using SpeechT5

---

# 📌 Key Takeaways

- Learned to use Hugging Face pre-trained models without training them.
- Explored multiple NLP pipelines using a unified API.
- Generated text, images, and speech with minimal code.
- Understood the difference between model training and inference.
- Built a strong foundation in Hugging Face Transformers and Generative AI.

---

# 📜 License

This repository is intended for educational and learning purposes.
