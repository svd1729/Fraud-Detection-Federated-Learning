# Fraud Detection using Vertical Federated Learning
## Introduction
In this project, I developed a Fraud Detection system using Vertical Federated Learning (VFL) to enable secure and privacy-preserving collaboration between multiple financial institutions. Unlike traditional centralized machine learning, Federated Learning allows training models on distributed data sources without directly sharing sensitive customer information. This is particularly crucial in financial domains where data privacy is a top priority.
## Datasets
Three different datasets were used, each representing a client in the federated setting. These datasets contained partially overlapping but mostly distinct features (vertical partitioning) for the same set of user transactions. Link of the datasets are given below:

• 📁 [Client 1 Dataset](https://drive.google.com/file/d/1n0jZZvy6XR-aVFgQDRMBuWDGhJE37cHt/view?usp=sharing)

• 📁 [Client 2 Dataset](https://drive.google.com/file/d/1O_MCVzxt2LOieGCIxx4vpH8PkRiYXSHI/view?usp=sharing)

• 📁 [Client 3 Dataset](https://drive.google.com/file/d/1Ju1HueDdqb7Gog9iHxeGK7mwABwz52rB/view?usp=sharing)
## Project Highlights
• Vertical Federated Learning Pipeline built from scratch using PyTorch and NumPy.

• Data Privacy preserved by keeping raw features decentralized at each client.

• Autoencoder-based feature transformation allowed different clients to contribute to a common global model.

• Federated Aggregation: Trained local models on each client, aggregated weights to form a generalized global model.
## Results & Analysis
The model successfully identifies fraudulent transactions in a highly imbalanced dataset. Despite a low precision due to the rarity of fraud, the high recall ensures that most fraudulent cases are flagged. This is acceptable for fraud detection systems where minimizing false negatives is crucial.

📉 Model Performance:

• Test Accuracy: 97.7%

• Precision (Fraud Class): 0.05

• Recall (Fraud Class): 0.80

• ROC-AUC Score: 0.607

## Author
Sourav Dhar

*B.Tech + M.Tech in Mechanical & Financial Engineering*

*Indian Institute of Technology, Kharagpur (IIT Kharagpur)*
