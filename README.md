# DeepNeuralNetworkFor-CarPricePrediction

Used Python in Jupyter Notebook and particularly Tensorflow, Sci-Kit Learn, Pandas, NumPy as well as Matplotlib and Seaborn for the visualizations.

At first some data validation takes place, giving a quick check over the main characteristics of our dataset. Inspecting for any missing values or identifying the included data types.

Later we go on with some more detailed analysis. Checking the distribution of the price values, examining characteristics of our dataset's variables as well as the relationships between them.

In the end we prepare our dataset to be applied in our Neural Network by dropping correlated features which might cause multicollinearity, changing datatypes, dealing with outliers, splitting features' values into groups-bins where necessary as well as transforming the target variable price to logarithmic scale. 
Last but not least, we split the dataset into training, validation and test subsets so that we avoid overfitting our model and we standardize our features since we notice a significant difference in their volumes.

All this data preprocessing makes us ready to fit our model and experiment with hyperparameters such as the amount of the hidden layers in our network and their respective size and activation functions, the loss function as well as the optimizer with its learning rate and more overfitting-preventing methods like batching or the maximum amount of training epochs.

# Results

After fine-tuning the hyperparameters and testing the model on the test subset which it has never seen before, we conclude with quite enthusiastic car price predictions where, the cases in which the predicted price was less than 10% away from the actual price (in absolute values), reach up to 98%! 

Of course there could definetely be a lot of space for progress, so i am looking forward to hearing for any corrections or improvements that you may think of.
