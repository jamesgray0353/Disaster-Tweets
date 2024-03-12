# Disaster Tweet Classification with gemma-7b-it

## Overview
This project explores the application of the gemma-7b-it model for classifying tweets into disaster-related or not. Utilising zero-shot learning and fine-tuning, we aim to accurately categorise tweets. An application of this could be to enhancing disaster response capabilities.

## Dataset
The dataset comprises tweets that have been manually tagged as either related to disasters or not. It originates from [Kaggle's NLP Getting Started competition](https://www.kaggle.com/c/nlp-getting-started). This is an open competition and providing a foundational basis for training and evaluating our model's performance.

## Environment Setup
- **Kaggle GPU**: P100 utilized for training and inference.
- **Python Packages**: torch, transformers, accelerate, bitsandbytes, datasets, trl, peft. Specific versions and installations are detailed within the notebook, addressing dependency conflicts and ensuring compatibility.

## Methodology
1. **Exploratory Data Analysis (EDA) and Preprocessing**: Initial data assessment and cleaning processes are applied to prepare the dataset into prompts for model testing and training.
2. **Zero-Shot Learning**: Initial model performance and different prompts.
3. **Model Training and Fine-Tuning**: Leveraging a pre-trained gemma-7b-it model, we apply fine-tuning techniques to adapt the model to our specific task of disaster tweet classification.
4. **Evaluation and Testing**: The model's performance is evaluated on metrics such as accuracy, precision, recall, and F1-score.

## Implementation Highlights
- **Quantization and Configuration**: Implementation details on model quantization and configuration for optimizing performance and efficiency.
- **Prompt Engineering**: Experimentation with different text cleaning and prompt structures on model performance.
- **Fine-Tuning Strategy**: Detailed steps on the fine-tuning process, including configuration and optimization techniques specific to our task.

## Results
Work in progress. The fine-tuning process significantly improves the model's ability to accurately categorize tweets (initial testing on small sample).
