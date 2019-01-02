# Task

Task of scene recognition starting with very simple methods: tiny images and nearest neighbor classification, and then move on to more advanced methods: bags of quantized local features and linear classifiers learned by support vector machines.

Experiments:

Tiny Image Representation + Nearest Neighbor Classifier

Bag of SIFT Representation + Nearest Neighbor Classifer

Bag of SIFT Representation + one-vs-all SVMs


## Results
Results are available in the ipynb directly.

1st: Tiny images representation and nearest neighbor classifier (accuracy of about 18-25%).

2nd: Bag of SIFT representation and nearest neighbor - classifier (accuracy of about 50-60%). 

3rd: Bag of SIFT representation and linear SVM classifier (accuracy of about 60-70%). 


## Implementation
Each of these tasks were mostly implemented from scratch; in some cases leveraging OpenCV functions.