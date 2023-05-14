# Deep-AUC-Maximization (DAM)
Secured 1st position at the project done as a part of ML Coursework(CSCE 633) under Dr. Tianbao Yang, Associate Professor, Computer Science &amp; Engineering, TAMU.

Collaborator: Anushka Garg

Problem Statement: LibAUC library was overfitting smaller dataset for AUCMLoss. We had to optimize AUCMLoss and compare with 7 datasets, namely BreastMNIST, PneumoniaMNIST, ChestMNIST, NoduleMNIST3D, AdrenalMNIST3D, VesselMNIST3D, SynapseMNIST3D. Among these seven datasets, ChestMNIST is a multi-label classification tasks, and others are binary classification tasks. For ChestMNIST, each label is considered as a binary classification problems. Except for ChestMNIST, other datasets are relatively small. Your goal is to improve the benchmark performance reported in the MedMNIST paper[Yang, J., Shi, R., Wei, D., Liu, Z., Zhao, L., Ke, B., ... & Ni, B. (2023). MedMNIST v2-A large-scale lightweight benchmark for 2D and 3D biomedical image classification. Scientific Data, 10(1), 41.]. For fair comparison, we had to use the same network structure as in the MedMNIST paper. 

Goal: This project aims to improve the generalization ability of DAM for medical image classification tasks.

Approaches used: 
1. Data Augmentation
2. Controlling Overfitting
3. Data Imbalance Handling
4. Hyper-training
5. Co-Training / Transfer Learning


