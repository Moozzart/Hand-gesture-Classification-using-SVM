# Hand-gesture-Classification-using-SVM
(The dataset can be obtained in the moodle --> MLFA course --> Hand gesture Classification using SVM)
There is a dataset of sign language using hand gestures. So there are 10 classes each classes having 3000 images. All the images are in RGB format. You need to perform the following steps.   

1. Convert the image into binary image. From each class in the dataset use 70% for training and 30% for testing.  

2. Extract features from these and store them in a csv file (features should be chosen by you - eg. binary pixel vectors, total number of white pixels, local binary patterns). Represent each image using such features. 

3. Use the features for classification using SVM (default setting). Print classification report.   

4. Apply grid search for hyper-parameter tuning.(eg: kernel, C, gamma).  

5. Report the model with best accuracy. If Memory error is coming you can rescale the image as per requirement.
