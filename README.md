# Kaggle-Competition--Digit-Recognizer-by-Ankita-
MNIST Digits - Classification Using SVM


MNIST Digits - Classification Using SVM¶
In this notebook, we'll explore the popular MNIST dataset and build an SVM model to classify handwritten digits. Here is a detailed description of the dataset.

http://yann.lecun.com/exdb/mnist/

We'll divide the analysis into the following parts:

Data understanding and cleaning
Data preparation for model building
Building an SVM model - hyperparameter tuning, model evaluation etc.

Data Understanding and Cleaning
Let's understand the dataset and see if it needs some cleaning etc.
Each digit/label has an approximately 9%-11% fraction in the dataset and the dataset is balanced. This is an important factor in considering the choices of models to be used, especially SVM, since SVMs rarely perform well on imbalanced data (think about why that might be the case

Data Preparation for Model Building¶
Prepare the dataset for building the model. We'll only use a fraction of the data else training will take a long time.

Model Building
Let's now build the model and tune the hyperparameters.Start with a linear SVM model first.
Non-Linear SVM -Then try a non-linear model with the RBF kernel.
Then Build the final model

Conclusion
The final accuracy on test data is approx. 92%. Note that this can be significantly increased by using the entire training data of 42,000 images (we have used just 10% of that!).
