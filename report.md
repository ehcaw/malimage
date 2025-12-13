# Machine Learning Final Project Report

Written by Daniel Quach, Joseph Nguyen, Ryan Nguyen

## 1. Introduction

### Background and Motivation

The objective of this project is to use various model architectures to classify whether or not software is malicious or not. The dataset contains software binaries that have been converted to images in .jpg format. We will use 5 different types of models: CNNs, NLP, SVM, KNN, and LS.

### Dataset Overview

The dataset contains images that were converted from software binaries. There are 24,000+ data points in the dataset, presplit into test, training, and validation datasets. The dataset is balanced, meaning there are roughly equal numbers of malicious images to benign images.

### Report Structure

The report is structured into 4 main sections: experimental design, implementation, comparison and analysis and the conclusions we drew.

---

## 3. Experimental Design

### Data Collection and Preprocessing

- **Data Sources**: Our dataset is a well structured dataset from Kaggle.
- **Data Cleaning**: The dataset is already clean, we would just have to convert the images into the various input forms of the models.
- **Feature Engineering**: [Describe how features were created/selected]
- **Data Splitting**: [Explain train/validation/test split strategy]

### Model Selection

We chose 5 different model types to attempt malware identification with.

- CNN:
- NLP:
- SVM:
- KNN:
- LS:

### Evaluation Metrics

- **Primary Metrics**: [e.g., Accuracy, Precision, Recall, F1-Score]
- **Secondary Metrics**: [e.g., AUC-ROC, Confusion Matrix, etc.]

### Experimental Setup

- **Hardware/Software Specifications**: [Describe computational environment]
- **Hyperparameter Tuning**: [Explain approach for hyperparameter optimization]
- **Cross-Validation Strategy**: [Describe validation approach]

---

## 4. Implementations

### Data Pipeline

[Describe the end-to-end data processing pipeline]

### Model Architectures

#### Model 1: [Model Name]

- **Architecture Details**: [Describe model structure]
- **Hyperparameters**: [List key hyperparameters and their values]
- **Training Procedure**: [Explain training process]

#### Model 2: [Model Name]

- **Architecture Details**: [Describe model structure]
- **Hyperparameters**: [List key hyperparameters and their values]
- **Training Procedure**: [Explain training process]

[Continue for all models implemented]

### Code Organization

[Describe the structure of your codebase and key modules]

### Challenges and Solutions

[Discuss implementation challenges and how they were addressed]

---

## 5. Comparison and Analysis

### Quantitative Results

| Model   | Accuracy | Precision | Recall  | F1-Score | AUC-ROC | Training Time |
| ------- | -------- | --------- | ------- | -------- | ------- | ------------- |
| Model 1 | [value]  | [value]   | [value] | [value]  | [value] | [value]       |
| Model 2 | [value]  | [value]   | [value] | [value]  | [value] | [value]       |
| ...     | ...      | ...       | ...     | ...      | ...     | ...           |

### Performance Analysis

- **Best Performing Model**: [Identify and justify]
- **Trade-offs**: [Discuss accuracy vs. interpretability, speed, etc.]
- **Error Analysis**: [Common patterns in misclassifications]

### Visualization Results

[Include plots and figures showing:

- Learning curves
- Confusion matrices
- Feature importance
- ROC curves
- Other relevant visualizations]

### Statistical Significance

[Discuss statistical tests if comparing models]

---

## 6. Conclusions

### Summary of Findings

[Recap the main results and achievements]

### Key Insights

[What did you learn from this project?]

### Limitations

[What are the limitations of your approach?]

### Future Work

- **Model Improvements**: [Potential enhancements]
- **Additional Features**: [New features to explore]
- **Extended Analysis**: [Further investigations]

### Real-world Applications

[Discuss how this work could be applied in practice]

### Final Remarks

[Concluding thoughts on the project]

---

## References

[List all papers, articles, and resources cited]

## Appendix

### A. Additional Results

[Supplementary tables and figures]

### B. Code Snippets

[Key code implementations]

### C. Data Samples

[Examples of preprocessed data]

### D. Hyperparameter Details

[Complete list of hyperparameters for all models]
