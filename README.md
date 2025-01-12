# Recommendation System using BERT4Rec with Temporal Attention

This repository contains a recommendation system developed as part of the **Applied Natural Language Processing** course at the University of Toronto. The project leverages the BERT4Rec model with temporal attention to provide optimized recommendations based on customer behavior.

## Project Overview
The recommendation system utilizes **BERT4Rec**, a transformer-based model tailored for sequential recommendation tasks. The model incorporates temporal attention mechanisms to enhance the understanding of time-based patterns in user interactions, improving prediction accuracy.

To make user-specific predictions, we utilized the authors, genres, descriptions of previously interacted books, and user rankings.

## Dataset
The system was trained on the [**Amazon Customer Reviews**](https://amazon-reviews-2023.github.io/) dataset, provided by UCSD. This dataset includes detailed customer reviews and purchase histories across multiple product categories, making it suitable for sequence-based recommendation tasks.

## Key Features
- **BERT4Rec Architecture:** Utilizes a bidirectional transformer for sequence modeling.
- **Temporal Attention:** Enhances recommendation accuracy by capturing time-sensitive patterns in user behavior.
- **Optimized Training:** Model training has been fine-tuned for improved performance and faster convergence.
- **Data Handling:** Efficient data preprocessing and handling for large-scale datasets.

## Challenges
One of the major challenges faced during this project was the size of the dataset and the limited computational power available. The large dataset file posed difficulties in fully utilizing the information for training purposes. Due to these constraints, we limited our training dataset to only 1% of the total samples, randomly chosen. This sampling was not sufficient to track all interactions between books and their patterns effectively. Despite these limitations, the model still offers some relatable recommendations, though the lack of sufficient training iterations and samples hindered the full potential of the model's performance.
