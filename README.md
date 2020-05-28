# Classification of Tumour and Normal Colon Tissues

This is a group project that I had done, together with [@JIALU355](https://github.com/JIALU355), [@hanggun](https://github.com/hanggun), and [@cantus-Jiale](https://github.com/cantus-Jiale), when we were taking the 'Data Mining and Exploration' course at the University of Edinburgh.

## About

Gene expression significantly aids in the development of efficient cancer diagnosis and classification platforms. In this project, we examined a colon cancer dataset that contains expression levels of 2000 genes taken from 62 colon tissue samples. Our aim was to classify the samples as cancerous or not. To reduce the data dimension and select the most useful features, we had considered four feature selection methods (F-test, TNoM, MFA, MFA+). Besides, we had also utilised five classification methods (linear SVM, Gaussian naive Bayes, k-NN, logistic regression, multilayer perceptron). Leave-one-out cross-validation (LOOCV) was performed on the training set, and Bayesian optimisation was used to find the optimal model hyperparameters. Lastly, three most robust classifiers were selected to classify the test set samples. We had found that linear SVM classifier, together with features selected using F-test, achieved the best generalisation performance.

## Disclaimer

Due to the fact that this is a project which might be reused for future students who take the 'Data Mining and Exploration' course at the University of Edinburgh, I am not including the codes for this project. However, I am happy to discuss more details regarding the project wherever possible.
