

**Image Anomaly Detection**

This code implements an image anomaly detection system using Fourier Transform and Canny Edge Detection. It detects anomalies in images by analyzing their frequency spectrum and edge information.

**Features**

1. Binary Labeling: The code assigns binary labels (0 or 1) to images as "good" or "anomalous" respectively based on the provided training and test data.
2. Anomaly Detection: Anomaly detection is performed by applying the Fourier Transform and Canny Edge Detection techniques to the preprocessed images.
3. Magnitude Spectrum: The code calculates the magnitude spectrum of the Fourier Transform to capture the strengths of different frequency components in the images.
4. Thresholding: Anomaly detection is based on thresholding the magnitude spectrum and combining it with the edge map obtained from Canny edge detection.
5. Evaluation of Accuracy: The code evaluates the accuracy of anomaly detection by comparing the predicted labels with the ground truth labels.
