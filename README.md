### About ###
We will be classifying the Simpson's MNIST data using an RGB and Grayscale one-vs-rest perceptron classification appraoch. In addition, we will evaluate the results and compare RGB against Grayscale.

### Features ###
- Grid Search over
  - Learning rates: 0.0001, 0.001, 0.01, 0.1
  - Initialization strategies: zero, constant, uniform, gaussian
  - Normalization techniques: minmax, gaussian, none
- Early Stopping during training after 10 epochs of no improvement
- Stores and uses best model with the best hyperparameters
- Evaluation of the model on 4 metrics, both overall and per class
  - Accuracy
  - Precision
  - Recall
  - F1 Score

### Files ###
- grayscale : This includes all of our grayscale images
- rgb : This includes all of our rgb images
- Simpsons.ipynb : This is our notebook that we trained the model and created our features on
- Report.pdf : A short report that highlights or training, hyperparameter tuning process and  analysis of results.

### Dependencies ###
- NumPy
- Python Imaging Library, PIL
- The OS library, os.
- copy (To make deep copies)
- matplotlib
- scikit-learn for the confusion matrix