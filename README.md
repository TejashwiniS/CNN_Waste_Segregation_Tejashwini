# Waste Material Segregation for Improving Waste Management
Problem Statement
Improper waste disposal contributes to environmental degradation, increased landfill waste and inefficient recycling processes. Manual sorting is labour-intensive, error-prone and costly. An AI-powered waste classification system addresses these challenges by streamlining waste segregation, reducing operational costs and improving recycling rates.

Key business benefits include:
Automated waste sorting, cutting time and labour
Increased recycling rated by precise classification of recyclables

Data Analaysis The dataset consists of images of different waste materials, stored in labeled folders corresponding to categories as follow
Cardboard
Glass
Metal
Paper
Plastic
Trash
Others
Findings on data Total image count 7625 across 7 categories All images are of equal size RGB images The data visualization section shows a moderate balance in catgeory distribution. Bar change of images counts per category Grid of sample images frm each category



Report model training results

Model Summary
3 Convalutional layers (32, 64, 128 filters) with Bacth Normialization and Max Pooling
Dropout layes(0.25 and 0.5)
Debse layer with 512 units followed by softmay output layer
Input size: (224, 244, 3)

Optimizer: Adam

Loss Function: Categorical Crossentropy

Traning config:

Epochs :20

Batch Size : 32

Validation: 20% test data

Performance:

Test Accuarcy : 59.80%

Classification Report: Includes recal, F1-score precision for each catehroy
