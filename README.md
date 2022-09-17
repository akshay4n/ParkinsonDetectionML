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

Concluding Remarks:<br>
* In this project, we leverage several unsupervised techniques, like PCA, LDA, etc. and supervised techniques, like SVM, Naıve Bayes, etc. for predicting Parkinson’s disease using the data of speech analysis. These methods provide highly accurate results.
* But there are some limitations in the methods in its robustness. That is, all of the models are based on two dataset Telemonitoring (TE) and Multiple Sound Recording (MSR).The model is easily influenced by longer samples, pitches of numerous range and some other data variance. The Jitter, Shimmer and Harmonicity features are not sufficient enough to detect the Parkinson’s disease, which was shown during the analsis of the dataset. But when considered the information of autocorrelation, range of the pitch, voice breaks, etc. makes the data more accurate.
* The project being highly accurate, reliable and efficient in detecting Parkinson’s disease, helps in early diagnosis of the deadly disease and serves the purpose of Artificial Intelligence and Machine Learning in the medical field.
