# Synthetic-Med_Data

This project generates synthetic medical datasets using the Synthetic Data Vault (SDV) library. It takes the UCI Heart Disease dataset, preprocesses it, and trains multiple generative models (Gaussian Copula and CTGAN) to create high-quality synthetic data for research and machine learning applications.

## Project Structure

- **Data Processing**: Loads raw data, handles missing values, and applies One-Hot Encoding and Scaling.
- **Synthesis**: Utilizes `GaussianCopulaSynthesizer` and `CTGANSynthesizer` to generate new samples.
- **Evaluation**: specific metrics (SDMetrics) are used to evaluate the quality and privacy of the synthetic data compared to the real distribution.
- **Visualization**: Compares distributions of real vs. synthetic columns.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd heart-disease-synthetic-data
