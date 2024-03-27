# FCN-ProteinStructure
This task need to build a Fully Convolutional Neural Network such as yolo series,and protein sequence data (also using PSSM Profiles) was used to predict protein secondary structure (H = helix, E = extended sheet, C = helix symbol).
The training dataset contains 7148 csv files and then there are 308 hidden test csv files.
The aim of the whole task is to make the triple classification prediction of proteins as high as possible，including the use of hyperparametric optimization and cross-validation techniques。

Protein structure prediction based on a full convolutional neural network, the final model has an accuracy of 79% on the test set and is in the top 20% of the Kaggle competition. Using DataLoader and AX hyperparametric optimizer.
5-Fold Corss-validation accuracy = 79.8%
![image](https://github.com/HelloLeexy/FCN-ProteinStructure/assets/76617194/2e7b2a79-8f57-4739-8d26-552ace379ae2)

