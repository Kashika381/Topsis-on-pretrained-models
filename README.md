# Topsis-on-pretrained-models
TOPSIS Analysis for Best Pre-Trained Model for Text Classification

Overview

This project applies the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to evaluate and rank pre-trained text classification models based on multiple criteria.

Methodology

We consider the following pre-trained models:

BERT

RoBERTa

DistilBERT

XLNet

T5

Evaluation Criteria

Each model is assessed using four key metrics:

Accuracy (Higher is better)

F1-Score (Higher is better)

Inference Time (ms) (Lower is better)

Model Size (MB) (Lower is better)

TOPSIS Steps

Normalization of the decision matrix.

Determine Ideal Best & Worst solutions.

Compute separation measures.

Calculate TOPSIS scores.

Rank models.

Installation & Execution

Clone this repository:

git clone https://github.com/yourusername/topsis-text-models.git
cd topsis-text-models

Install dependencies:

pip install numpy pandas matplotlib

Run the Python script:

python topsis_analysis.py

Output

A ranked list of models based on their TOPSIS scores.

A bar chart visualization of the rankings.

Results Interpretation

The TOPSIS Score determines how close each model is to the ideal solution. The model with the highest score is the most suitable based on the chosen criteria.

Contributions

Feel free to contribute by improving the evaluation criteria, adding new models, or refining the methodology!

