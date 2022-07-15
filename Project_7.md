
# [The application of machine learning to predict genetic relatedness using human mtDNA hypervariable region I sequences](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0263790)

## Background
This projects addresses the curiosity and interest in Machine Learning and some statistical analysis. 

## Abstract
Human identification of unknown samples following disaster and mass casualty events is essential, especially to bring closure to family and friends of the deceased. Unfortunately, victim identification is often challenging for forensic investigators as analysis becomes complicated when biological samples are degraded or of poor quality as a result of exposure to harsh environmental factors. Mitochondrial DNA becomes the ideal option for analysis, particularly for determining the origin of the samples. In such events, the estimation of genetic parameters plays an important role in modelling and predicting genetic relatedness and is useful in assigning unknown individuals to an ethnic group. Various techniques exist for the estimation of genetic relatedness, but the use of Machine learning (ML) algorithms are novel and presently the least used in forensic genetic studies. In this study, we investigated the ability of ML algorithms to predict genetic relatedness using hypervariable region I sequences; that were retrieved from the GenBank database for three race groups, namely African, Asian and Caucasian. Four ML classification algorithms; Support vector machines (SVM), Linear discriminant analysis (LDA), Quadratic discriminant analysis (QDA) and Random Forest (RF) were hybridised with one-hot encoding, Principal component analysis (PCA) and Bags of Words (BoW), and were compared for inferring genetic relatedness. The findings from this study on WEKA showed that genetic inferences based on PCA-SVM achieved an overall accuracy of 80–90% and consistently outperformed PCA-LDA, PCA-RF and PCA-QDA, while in Python BoW-PCA-RF achieved 94.4% accuracy which outperformed BoW-PCA-SVM, BoW-PCA-LDA and BoW-PCA-QDA respectively. ML results from the use of WEKA and Python software tools displayed higher accuracies as compared to the Analysis of molecular variance results. Given the results, SVM and RF algorithms are likely to also be useful in other sequence classification applications, making it a promising tool in genetics and forensic science. The study provides evidence that ML can be utilized as a supplementary tool for forensic genetics casework analysis.


## Your Task
1. Reproduce the work done using machine learning
2. Explore alternatives algorithms and approaches to addressing the questions


## Questions
In your report, you should address the following question:
- Are you able to arrive at similar conclusions as those in the paper? Why or why not? 
- What else can you glean from your re-analysis?
- Are the descriptions in the methodology section detailed for reproducibility? If not, what could you have done to improve reproducibility?
