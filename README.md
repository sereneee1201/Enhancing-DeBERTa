# AIST3120 Final Project – Enhancing DeBERTa for Named Entity Recognition

This project explores methods to improve DeBERTa for the Named Entity Recognition (NER) task on the CoNLL-2003 dataset. It is the final project for the AIST3120 Artificial Intelligence course.

## 🧠 Project Goals
- Fine-tune DeBERTa on the CoNLL-2003 dataset using a Conditional Random Field (CRF) layer on top.
- Apply token-level data augmentation (e.g., synonym replacement) to improve model generalization.
- Evaluate model performance using accuracy and F1 score.

## 🛠️ Methods Used
- **Model**: DeBERTa (HuggingFace Transformers) + CRF
- **Data**: CoNLL-2003 (NER dataset with PER/ORG/LOC/MISC tags)
- **Augmentation**: Synonym replacement using WordNet
- **Training Framework**: PyTorch & Hugging Face Transformers
- **Evaluation Metrics**: Accuracy, F1 Score

## 📁 Project Files
- Project report: Comprehensive report on our project
- AIST_3120_Project_without_outputs: Notebook with **outputs removed** (renderable on GitHub)
- AIST_3120_Project_with_outputs: Notebook with **full outputs**
Please use the first notebook for quick review on GitHub, and the second one for reviewing results.
