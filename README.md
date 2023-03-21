# **SVM Python**

SVM stands for Support Vector Machine, which is a type of supervised learning algorithm used for classification and regression analysis. The basic idea of SVM is to find the optimal hyperplane that separates the input data into different classes in a high-dimensional space. 






> Code T8-1 : We created some data in the variables X, Y, of which we used the scikit-learn library with SVM to generate the separating hyperplane from this data.


> Code T8-2 : We used the make_blobs dataset from scikit-learn to create an interactive graphical interface for exploring the results of an SVM model on different dataset sizes, leveraging the ipywidgets library and SVC from sklearn.svm. 

> Code T8-3 : We used SVC with the make_circles and make_blobs datasets to then visualize the kernel and decision function. Finally, we compared two SVM models with different values of C in a 2D classification problem and visualized the decision function and support vectors of each model.

> Code T8-4 : Facial Recognition, using the fetch_lfw_people dataset and leveraging 3 modules from the scikit-learn library: SVC, RandomizedPCA, and make_pipeline. We created a classification model where we set 150 principal components in order to normalize the features. The objective is to identify the person who appears in the photo, and at the end, we print the incorrect classifications that the model made in red, along with the classification report and confusion matrix.

> Code T8-5 : With the iris dataset, we implemented different SVC models, modifying the kernel; linear, rbf, sigmoid, poly, trying to find which one generates a better decision function. At the end, we have an interactive classification where the user can modify the C, gamma, and kernel variables to see the behavior of the model. 

> Code T8-6 : We implement an SVM for regression, creating the data in the variables X, Y, and creating the regression and its graphical visualization for each of the SVMs: linear, radial, polynomial. 

## **Datasets**
*   make_blobs
*   make_circles
*   fetch_lfw_people
*   iris



