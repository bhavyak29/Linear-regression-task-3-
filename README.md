# Linear-regression-task-3-

I started by importing the necessary Python libraries for data handling, visualization, and building a machine learning model. Then, I loaded a housing dataset (Boston Housing) directly from a URL and displayed the first few rows to understand its structure.

Next, I selected a single feature ('rm', the average number of rooms) to predict the target variable ('medv', the median home value). I split the data into training and testing sets so that the model could learn on one part and be tested on unseen data.

After that, I created and trained a linear regression model using LinearRegression() from sklearn. Once the model was trained, I made predictions on the test data.

To evaluate how well the model performed, I calculated MAE (Mean Absolute Error), MSE (Mean Squared Error), and R² score — all standard regression metrics.

Finally, I plotted the regression line over the actual data to visualize how closely the model’s predictions match the real values. I also printed the model’s intercept and coefficient to interpret the relationship between the number of rooms and home prices.
