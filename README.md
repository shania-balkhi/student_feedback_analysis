This repository contains code to a project, which aims to evaluate three machine learning algorithms, 
one each of supervised (**Support Vector Machine**), unsuperised (**Agglomerative Hierarchical Clustering**), 
and semi-supervised (**Self-Training Classifier**).

## Training Dataset Details
The dataset used to train the models has 450 entries, comprising of 15 teachers, with each teacher having 
30 review entries to their name.

See the file `final_complete_teacher_dataset.csv` for the training dataset.

## Testing (Benchmark) Dataset Details
A uniform benchmark dataset of 250 entries has been used to test the performance of the models and analyse 
their performance. The testing dataset is similar to the training dataset.

See the file `benchmark_dataset.csv` for the testing dataset.

## Evaluation Metrics
The performance of the above algorithms has been tested against the benchmark dataset, and the confusion 
matrix, as well as F1-score for each algorithm is included in the respective codes.
