# Character classification using Random Forest Classifier in Python

This works aims to classify characters from Google Street View images. It involves extracting the data to desired format from the dataset, create training and test data sets, use supervised learning to build Random Forest Classifier, predicting the test data using the model.

The libraries numpy, pandas were used for processing data efficiently in Python. Scikit-learn is used to build a Random Forest Classifier. The working environment included Jupyter Notebook and Anaconda.

The model achieved a prediction accuracy of 44.5% on the test images. For reference, the benchmarks (using Julia) for Random Forest and kNN were 42.93% and 40.57% respectively. The maximum score at the time of this writing was 85.43%.
So evidently there is a lot of scope of improvement. But this was expected because of the following reasons.
The parameters for the Random Forest Classifier was not tuned and optimised instead a default set of parameters were used.
Further it is well known that for tasks such as image classification, methods such as Neural network usually outperforms Random Forest Classifiers.

The future work should therefore try to optimise the Random Forest Classifier and consider using deep learning to classify the images.


