# XAI with TabNet: Contrastive and Counterfactual Explanations for Credit Risk

This project explores explainability in credit risk prediction using a TabNet model trained on Lending Club data. We apply several interpretability techniques to understand and audit the model's decisions:

### Methods Used
- **Contrastive explanations**: Find the minimal feature differences between samples with opposite predictions.
- **Greedy counterfactual search**: Flip model predictions by iteratively adjusting input features.
- **SHAP (from scratch)**: Attribute model output to individual features for both local and group-based fairness analysis.

### Fairness Auditing
Explanations are broken down across income groups and verification status to check whether the model behaves differently for different users — even when predicting the same outcome.
