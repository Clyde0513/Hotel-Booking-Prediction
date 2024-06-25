# This is my first data science project where I analyze two different datasets: UCI Heart Disease and Hotel Booking and use different models to see which one has the highest predictive accuracy

TO INSTALL the required packages, install PIP first then install: scikit-learn1.4.1.post1, numpy1.26.4, scipy1.12.0, pandas2.2.1, matplotlib3.8.3, jupyterlab4.1.5

To summarize my findings, I have used a model called RandomForest that fits a decision tree classifiers on various sub-samples of the dataset, and then averaging to improve its predictive accuracy and control over-fitting. Since the dataset is huge, roughly 69k samples, this model is accurate because it constructs multiple decision trees at the same training time. Lastly, it handles non-linearly data well. As a result, I got an accuracy of roughly 88% to predict whether a hotel booking will be canceled or not!
