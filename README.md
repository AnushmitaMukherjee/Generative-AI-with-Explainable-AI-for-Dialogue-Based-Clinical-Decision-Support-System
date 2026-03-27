# Generative AI with Explainable AI for Dialogue-Based Clinical Decision Support System

## Overview

This project focuses on developing a dialogue-based clinical decision support system using generative AI and explainable AI techniques. The system is designed to process patient symptom descriptions and generate clinically relevant responses that can assist in preliminary medical reasoning.

The primary goal is to support healthcare professionals by providing structured and interpretable insights, rather than replacing clinical expertise.

---

## Objectives

* Build a dialogue-based system for handling clinical queries
* Generate context-aware responses using a transformer-based model
* Integrate explainability techniques to improve transparency
* Enhance trust in AI-assisted clinical decision support

---

## Methodology

### Data Processing

Patient symptom descriptions are cleaned and preprocessed to ensure consistency and meaningful input to the model.

### Model Development

A fine-tuned FLAN-T5 model is used to generate responses based on input symptoms. The model is trained to produce coherent and contextually relevant outputs.

### Explainability

SHAP-based techniques are applied to interpret model predictions and highlight important features contributing to the generated responses.

### Output Generation

The system provides both a generated response and an explanation to improve interpretability.

---

## Model Details

* Model: FLAN-T5 (fine-tuned)
* Task: Clinical text generation
* Input: Symptom descriptions
* Output: Generated clinical insights

---

## Evaluation

The model is evaluated using:

* BERTScore
* Semantic similarity metrics
* Qualitative analysis of responses

---

## Project Structure

```
data/            Dataset files  
notebooks/       Jupyter notebooks  
src/             Source code  
models/          Saved models  
results/         Output results  
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the project

```
python main.py
```

---

## Limitations

* The system has not been validated by clinical professionals
* Evaluation metrics do not fully capture clinical correctness
* Further testing is required for real-world deployment

---

## Future Work

* Incorporate clinical validation
* Improve model robustness and accuracy
* Extend to real-time or web-based applications
* Explore advanced explainability techniques

---

## Author

Anushmita Mukherjee
M.Sc. Thesis Project
