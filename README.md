# AI Midterm Project

In this project, you will build a regression model and a classification model from scratch. Please follow the instructions closely, and only use Python's Numpy, Pandas, and matplotlib library to complete this project. Using functions from sklearn is not allowed.

Part I: A Regression Model

In this part, please build a multilinear regression model that extracts the relationship between housing prices and other relevant variables. 


Task 1: Data Transformation (10 pts)

                          Create a new column named "Age" that represents the age of each house when it was sold.


Task 2: Train a Multilinear Model (20 pts)

                          Assume that the price can be expressed as a linear combination of age, bedrooms, total area, and quality:

                          Price= θ0 + θ1 ⋅ Age + θ2 ⋅ Bedrooms + θ3 ⋅ TotalArea + θ4 ⋅ Quality.

                          Apply the normal equation to find the best values for the parameters:
                          1.	Construct matrix X and y (the matrices are defined in Week 6 notebook and Chapter 4 of the textbook).
                          2.	Calculate the parameter vector using the normal equation θ=(XT⋅X)−1⋅XT⋅y


 Task 3: Make A Prediction (10 pts)

          Suppose that there is another house with the following attribute:
          •	YearBuilt: 1985
          •	YearSold: 2021
          •	Bedrooms: 6
          •	Total Area: 2500
          •	Quality: 5.5
          Use the parameter values that you have calculated to make a prediction on its sale price.



Part II: A Classification Model

  In this part, we will build a logistic regression model and evaluate its performance on the classifying the data.


Task 1: Data Visualization (10 pts)

                          Visualize the data as a scatter plot. Show class 0 records as green dots and class 1 records as blue dots. Display the following items:
                          •	Title of the plot: Distribution of the training data
                          •	Label for x axis: x1
                          •	Label for y axis: x2
                          •	Legend


Task 2: Apply A Logistic Regression Model (10 pts)

                          Suppose that you are given a logistic regression model with explicity paramter values:
                          p=σ(x⋅θT).
                          where
                          •	p: the probability that the point belongs to class 1.
                          •	x=(1,x1,x2).
                          •	θ=(θ0,θ1,θ2)=(−2.15,0.92,−0.82).
                          •	σ(t)=11+e−t
                          Find the model's prediction


Task 3: Model Evaluation (40 pts)

                          Calculate the following model metrics regarding the performance on the test set:
                          •	classification accuracy
                          •	precision score
                          •	recall score
                          •	F-1 score



