Parkinsons' Disease Detection using Machine Learning
<br>
In this project we compare multiple classifier algorithms and analyze their accuracy, namely; SVM classifier, Random forest classifier, Decision tree, Naive bayes and Neural network.
<br>
Objectives
* Build a model to detect the presence of Parkinson’s disease in an individual.
* Early Detection of the disease to facilitate clinical monitoring of elderly people and increase their life span.
* Compare multiple classifier algorithms and analyze their accuracy.

The following table shows some previous works associated with the topic:<br>
![img1](/visualizations/relatedWorks.jpg)

Methodology:<br>
1. Data-set information<br> Disease Classification (DC) Dataset, Multiple Sound Recording (MSR) Dataset, Telemonitoring (TE) Dataset
2. Analyzing data-sets
3. Data visualization and covariance matrices
4. Dimensionality Reduction
    1. PCA
    2. LDA
5. Training Different Classifier Algorithms
    1. SVM Classifier
    2. Random Forest Classifier
    3. Decision Tree
    4. Naive Bayes
    5. Neural Network

EXPERIMENTAL RESULTS AND ANALYSIS 
<br>
* Correlation Matrices
    * Multiple Sound Recording Datasets for Training Correlation Matrix:<br>![img1](/visualizations/multiple-sound-recoring-train-correlation-matrix.jpg)<br>
    * Multiple Sound Recording Datasets for Testing Correlation Matrix:<br>![img1](/visualizations/multiple-sound-recoring-test-correlation-matrix.jpg)<br>
    * Telemonitoring Dataset Correlation Matrix:<br>![img1](/visualizations/telemonitoring-correlation-matrix.jpg)<br>
* Dimensionality reduction using PCA and LDA
    * PCA Variance:<br>![img1](/visualizations/PCAVariance.png)<br>

    * PCA and LDA on MSR-training and Telemonitoring dataset:<br>![img1](/visualizations/PCA_LDA_TE_MSRtrain.jpg)
* Accuracy
    * Accuracy of algorithms before combination of MSR and TE datasets:<br>![img1](/visualizations/g1.png)

    * Accuracy of algorithms after combination of MSR and TE datasets:<br>![img1](/visualizations/g2.png)
