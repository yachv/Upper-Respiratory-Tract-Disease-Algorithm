# Upper Respiratory Tract Disease (URTD) Diagnosis Algorithm

## Introduction
The Upper Respiratory Tract Disease (URTD) Diagnosis Algorithm is a tool designed to assist veterinary professionals in diagnosing and managing cats with URTD.

## About the Algorithm
The algorithm guides users through a series of questions related to the cat's clinical signs and medical history. Based on the user's input, the algorithm provides recommendations for the diagnosis and treatment of URTD.

## Features
- User-friendly interface for inputting cat-related information.
- Provides evidence-based recommendations for URTD diagnosis and management.
- Offers further recommendations based on user input.

## Usage
To use the algorithm, follow these steps:

1. Run the `diagnose_urt.py` file.
2. Answer the prompts regarding the cat's signs of URTD.
3. Follow the recommendations provided by the algorithm.

## Example Usage
```python
cat_signs_input = input("Is the cat exhibiting signs of Upper Respiratory Tract Disease (URTD) with a duration of ≤10 days? (yes/no): ")
diagnose_urt(cat_signs_input)
