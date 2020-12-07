# Detect-damage-due-pesticide

Python is used to do all the process, training, and testing for pesticide dataset. All the processes are done using Python3 Google Colab. To tackle this problem, I started with data preparation by deleting messing values and visualizing the data using a bar plot, histogram, heatmap correlation. After that, I preprocessed the data and ended up splitting the data into training and testing sets. I applied more than one machine learning algorithms in a single method which are:
o	Logistic Regression
A machine learning algorithm classification used to predict and return the probability of the target variable. In my project the attribute (Corp_Damage) which holds three possible variable values (0,1,2) meaning (alive, damage due other causes and damage due pesticides) respectively.
o	Decision Tree Classifier
It is a type of supervised machine learning for classification. It can handle categorical variables (yes/no types).
o	Random Forest Classifier
It is one of the most accurate learning algorithms. Also, it runs efficiently on large dataset.
o	K-Nearest Neighbors (KNN) Classifier
It is very simple in implementation and classes do not have to be linearly separable.
o	Artificial Neural Network (ANN) Classifier
It can detect complex nonlinear relationships between dependent and independent variables and the ability to detect all possible interactions between the predictor variables.
o	Support Vector Machine (SVM) Classifier 
It gives high accuracy in terms of binary classification.

They are used for classification problems. Furthermore, I applied model evaluation to test the model's accuracy using a confusion matrix and finally, I compared the predicted results with the actual ones. I come up that the model with the highest accuracy is Artificial Neural Network (ANN).
