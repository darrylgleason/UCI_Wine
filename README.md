This work is used to evalute the University of California Urvine (UCI) "Wine" data set. The intent is to evaluate various classification models and accurately predict a wine's class based on 13 features including its alcohol content, color intensity, etc.

The data is imported and processed before a (1) k-nearest neighbors (kNN) and (2) support vector machine (SVM) model are used to make predictions. Both methods' hyperparameters are chosen using grid--searches with cross-validation.

When trained on half the data set, the SVM model is shown superior to the kNN model, each garnering accuracy scores of ~0.96 and ~0.73, respectively. When trained on the full data set, both models tend to perfectly (or near perfectly) predict all wine classifications - syptomatic of overfitting. Additional data would be needed to cross-validate these models.
