# Multiple-Object-Classification
A Classifier to find the largest digit in a modified version of MNIST that contains multiple digits in an image.

This project was originally made on Colab. To replicate results it is recommended to initiate a similar environment. 

## Running the Jupyter Notebook
To run our code please run all the cells downward until you reach the “Evaluation models” tab. From there run the desired sub-tab to run different models.

You will have the following sub tab options:

	- Neural Network ( the neural net implemented by hand)
	- Transfer learning attempt (using Keras)
	- Simple CNN (using Keras)
	- Cross Validation (using Keras), example of how we did hyper parameter tuning and cross validation
	- SVM with preprocessed data
	- Baseline SVM

Be wary of global variables, make sure to run all code for within each sub-tab to get the correct setup for the model.

After the “Evaluation models” tab, the rest of the code is just for getting the correct format and submitting to Kaggle and can be ignored.

Note: The new_data function runs all preprocessing on a given array of inputs, x. You are able to run variations of preprocessing by changing between parameters “find_largest_count_ratio” and “find_largest_axes” which are two different methods of preprocessing.

Furthermore, to load data in the Virtual Machine, you will be prompted to login and authenticate on google drive. This is because we use the Kaggle API to load the files directly.

#### All code is property of Daoud Piracha and Nadeem Ward.
