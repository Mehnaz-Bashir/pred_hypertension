# Hypertension Risk Prediction AI

*Machine learning model for accurate hypertension staging with 97.7% accuracy*

## 🔍 Project Overview
This project develops a **stacked ensemble machine learning model** to predict hypertension stages with clinical-grade accuracy. Key achievements:
- **97.7% overall accuracy** (outperforming single models by 25-30%)
- **100% recall for Stage 2 hypertension** - critical for preventing missed diagnoses
- **Interpretable AI** with clinically meaningful features (BMI-Stress interaction, Lifestyle Score)

## 🏆 Key Features
- **Advanced Model Architecture**: Stacked ensemble combining Random Forest, SVM, and logistic regression
- **Clinical Interpretability**: 
  - Feature importance analysis revealing top predictors
  - Decision tree visualization of splitting logic
- **Practical Implementation**:
  - EHR-compatible outputs
  - Probability thresholds optimized for clinical safety

## 📊 Model Performance

| Metric               | Stacked Ensemble | Random Forest | SVM       |
|----------------------|------------------|---------------|-----------|
| **Accuracy**         | 97.7%            | 72.1%         | 95.2%     |
| **Stage 2 Recall**   | 100%             | 85%           | 98%       |
| **F1-Score**         | 97.5%            | 70.3%         | 95.0%     |
