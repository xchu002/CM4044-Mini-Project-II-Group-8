# CM4044-Mini-Project-II-Group-8
Predicting molecular LogP from RDKit descriptors using classical machine learning, feed-forward neural networks, and an RBF neural network.

Special thanks to Ong Jaymee and Tiffany Ong Ting Ting for being my groupmates.

This repository contains code from an undergraduate group project exploring the prediction of molecular LogP values from molecular structures. RDKit was used to calculate molecular descriptors, followed by feature selection and the evaluation of several regression approaches, including linear models, support vector regression, k-nearest neighbours, decision trees, random forests, gradient boosting, feed-forward neural networks, and a radial basis function neural network. The original notebooks were subsequently cleaned and updated for compatibility with current Python libraries.

After hyperparameter tuning, Support Vector Regression achieved the strongest test performance, with an R2 of 0.973 and an MSE of 0.0452. The optimized feed-forward neural network achieved an R2 of 0.933, while the RBF neural network achieved an R2
of 0.917. These results showed that the tuned classical machine-learning models, particularly SVR, performed better than the neural-network architectures tested in this project.
