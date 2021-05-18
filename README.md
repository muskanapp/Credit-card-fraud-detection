# Credit-card fraud detection
I have done some exploratory data analysis and visualization on the data. Since this is a highly unbalanced dataset , I have used under-sampling to make balanced dataset for model training .I have used various algorithms and in the end I found Random Forest to be the most effective. Thus I have used it as the model for doing the final testing on the dataset.
Figures after testing the Random forest model on the test set.
1. Accuracy - 93.93 %
2. Precision - 95.23%
3. Recall- 86.96%
4. F1-score - 90.90 %

In the 2nd notebook, I have used a deep learning model which is 5 layers deep.
Figures after testing the DNN model on the test set.
1. Accuracy - 99.93 %
2. Precision - 84.67%
3. Recall- 78.91%
4. F1-score - 81.69 %

After that I have used an oversampling method SMOTE to solve the problem of imbalanced data-set.
Figures after testing the DNN model on the test set.
1. Accuracy - 99.68 %
2. Precision - 99.76%
3. Recall- 99.61%
4. F1-score - 99.68 %

Thus a deep learning model with SMOTE gives the best performance.
