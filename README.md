# OptunaDataTune (or ML-HyperSampling)

This repository demonstrates the combined use of Optuna for hyperparameter optimization and various sampling techniques for handling imbalanced datasets in machine learning.

## Description

This project aims to improve model performance by:

1. **Optimizing Hyperparameters with Optuna:** We leverage Optuna's efficient search algorithms, particularly TPE, to find the best hyperparameter settings for different models.

2. **Addressing Imbalanced Data:** We explore the impact of undersampling and oversampling methods on model performance, especially for imbalanced datasets.

## Repository Structure

* **`optuna_optimization/`:** Contains code for hyperparameter tuning using Optuna.
* **`sampling_techniques/`:** Implements different undersampling and oversampling techniques.
* **`data/`:** Stores the datasets used for experimentation.
* **`requirements.txt`:** Lists the necessary Python libraries.

## Usage

1. **Installation:** Install the required libraries: `pip install -r requirements.txt`
2. **Hyperparameter Optimization:** Run the scripts in `optuna_optimization/` to perform hyperparameter tuning.
3. **Data Balancing:** Use the scripts in `sampling_techniques/` to apply undersampling or oversampling to your dataset.
4. **Model Training and Evaluation:** Train and evaluate your chosen model with the optimized hyperparameters and balanced dataset.

## Results

Our research shows that combining Optuna and sampling techniques significantly improves model performance on imbalanced datasets. We observed improvements in metrics such as F1-score and AUC.

For detailed results and visualizations, please refer to the associated research paper.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your suggestions or improvements.
