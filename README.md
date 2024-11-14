# TikTok Video Classification: Claims vs. Opinions

## Project Overview
This project aims to develop a machine learning model that classifies TikTok videos as either "claims" or "opinions" to prioritize videos for human review. The goal is to identify videos that make claims, as they are more likely to violate platform terms of service.

## Problem Statement
TikTok receives numerous user reports about videos, and not all can be reviewed manually. Identifying videos that make claims helps prioritize those for review based on engagement data, which correlates strongly with claim status.

## Model Overview
The data team built two tree-based classification models: **Random Forest (RF)** and **XGBoost**. Both models were evaluated on a validation dataset, and the model with the highest recall score was selected for final deployment.

- **Champion Model**: Random Forest (Recall: 0.995)
- **Test Dataset**: Final model performance was evaluated on a held-out test dataset to estimate future performance.

## Key Findings
- **Model Performance**: The RF model outperformed XGBoost in terms of recall, making it the best choice for identifying claim videos.
- **Impact**: The model helps prioritize video reviews, ensuring content that violates TikTok's terms of service is flagged promptly.

## Technologies Used
- **Python**: For data analysis and model development (Pandas, Scikit-learn, XGBoost)
- **Jupyter Notebooks**: For model training, evaluation, and documentation
- **GitHub**: Version control and project hosting

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SUWAANsilveroak/TikTok-project.git
