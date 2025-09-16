Project Overview

As part of my AI & Machine Learning internship at BroskiesHub, I completed a project focused on building a Linear Regression Model to predict housing prices using the California Housing dataset. The goal was to apply machine learning concepts learned during the course in a practical, real-world scenario.

✅ How I Completed the Project

Dataset Collection and Exploration
I used the California Housing dataset available in scikit-learn. I loaded the data into a Pandas DataFrame and performed exploratory data analysis (EDA) to understand the distribution and relationships between features and the target variable (MedHouseValue).

Feature Selection
For simplicity, I selected one key feature (AveRooms – Average Number of Rooms) to predict the median house value. This allowed me to focus on understanding the basic linear relationship between variables.

Data Splitting
I split the dataset into training and testing sets using train_test_split, reserving 20% of the data for testing to evaluate the model’s performance.

Model Training
I implemented a Simple Linear Regression model using scikit-learn’s LinearRegression. I trained the model on the training dataset.

Predictions and Evaluation
After training, I predicted housing prices on the test set and evaluated the model’s performance using important metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Visualization
I created scatter plots to visualize the relationship between the input feature and the target variable, and to compare actual vs predicted values.

Documentation and Submission
I documented the full process in a Jupyter Notebook, including code, visualizations, and conclusions, and uploaded the project to GitHub for submission.

💡 What I Learned

The full machine learning workflow: from data preprocessing and exploration to model building and evaluation.

How to use scikit-learn’s train_test_split, LinearRegression, and performance metrics (MAE, RMSE).

Importance of visualizing data to better understand feature-target relationships.

How to handle real-world datasets and deal with feature selection in a practical setting.

How to document a data science project properly for reproducibility and clarity.

How to use GitHub for version control and project sharing.

🚀 Outcome

By completing this task, I developed confidence in implementing basic machine learning algorithms and gained hands-on experience in supervised learning and regression tasks. This project helped me build a solid foundation for more advanced machine learning projects in the future.
