# Classification

## Logistic Regression
It is the go-to method for binary classification problems (problems with two class values).

	y = b0 + b1 * x       //Linear Regression
	p = 1 / ( 1 + e^( -y ) )       //Sigmoid Function
	ln ( p / ( 1 - p ) ) = b0 + b1 * x      //Logistic Regression

## K-Nearest Neighbors (K-NN)
	1. Choose the number of K of neighbors (commonly k=5 or 10).
	2. Take the K nearest neighbors of the new data point, according to the Euclidean distance or other distances.
	3. Among these K neighbors, count the number of data points in each category.
	4. Assign the new data point to the category where you counted the most neighbors.
	5. Model is ready!!
  
    Euclidean Distance = ( ( x2 - x1 ) ^2 + ( y2 - y1 )^2 )^(1 / 2 )  
   
## Support Vector Machine
   An SVM model is basically a representation of different classes in a hyperplane in multidimensional space. The hyperplane will be generated in an iterative manner by SVM so that the error can be minimized. The goal of SVM is to divide the datasets into classes to find a maximum marginal hyperplane (MMH).

