# Physician_Risk

Input data is physician annual aggregated billing data, along with patient cohort description. The data is unlabeled with whether a physician is fraudulent. So to predict fraudulent physicians, we use unsupervised learning anomaly detection to calculate a risk score for the physicians. We implemented various methods including Gaussian probabilities, Gaussian mixture models, PCA, self-organizing maps, and Boltzmann machines. However, our autoencoder demonstrated the best performance. 
