# TumorClassification-
In this challenge, we implemented Logistic Regression combined with Principal Component Analysis (PCA) to classify breast tumors as benign (B) or malignant (M). PCA was used to reduce the high-dimensional dataset into a smaller set of principal components, capturing the most significant variance while simplifying the model. We then applied StandardScaler to ensure that all features contributed equally to both the PCA transformation and Logistic Regression. This prevented features with larger ranges from dominating the analysis.

The Logistic Regression model was trained and achieved 100% accuracy on the validation set, effectively distinguishing between benign and malignant tumors. After validating the model, we made predictions on the test data and mapped the results back to the original labels (B for benign and M for malignant).

This approach allowed us to build a robust and scalable model, reducing feature dimensionality and computation time while maintaining high predictive accuracy. The combination of PCA and Logistic Regression provided a highly efficient and accurate solution for this classification task.
