# IPL-Score-Predictor
![image](https://user-images.githubusercontent.com/60037478/230733764-20b5ef46-123a-4e0f-8c52-4a5f29016cdb.png)
<br>
This is a project that predicts the outcomes of IPL (Indian Premier League) matches using Ridge Regressor and Flask. Python and scikit-learn are used to build the project.
<br>
<h1>Getting Started</h1>
get started with this project, you'll need to do the following:

Clone this repository to your local machine.
Run the Flask app using python app.py.
<h1>How to Use</h1>

After the Flask app is up and running, you can use the web interface to enter the names of the teams and the location of the match, and the software will predict the result using Ridge Regressor. If you like, you can also download the dataset and train the model yourself.

<br>

![image](https://user-images.githubusercontent.com/60037478/230734037-7aa865ed-3aa0-4549-89c1-875a29112e62.png)
<br>
<h1>FILES</h1>
<br>
app.py: the Flask app that handles the user interface and prediction.<br>
model.py: the script that trains the Ridge Regressor model on the IPL dataset.<br>
ipl.csv: the IPL dataset used for training the model.<br>
home.html: the HTML template for the user interface.<br>
style.css: the CSS stylesheet for the user interface.<br>
<h1>DATASET</h1>
<br>
The IPL dataset used in this project is available on Kaggle. It contains data on all IPL matches played between 2008 and 2020, including the teams, venues, and outcomes<br>
<h1>Data Cleaning and Preprocessing</h1>
<br>
Exploring and understanding the IPL dataset<br>
Handling missing and inconsistent data<br>
Encoding categorical features like teams and venues using one-hot encoding or label encoding<br>
Splitting the dataset into training and testing sets<br>
Model Selection and Training<br>
Choosing a suitable machine learning model for the task of IPL prediction<br>
Evaluating different models and selecting the best one based on metrics like accuracy and mean squared error<br>
Tuning hyperparameters of the selected model using techniques like cross-validation<br>
Training the final model on the entire training dataset<br>
<h1>Flask App Development</h1><br>
Creating the Flask app and setting up routes<br>
Handling user inputs using HTML forms and processing them in the Flask app<br>
Loading the trained Ridge Regressor model and making predictions using it<br>
Displaying the prediction results to the user through the web interface<br>
<h1>Deployment</h1>
Hosting the Flask app on a cloud service like Heroku <br>
Configuring the app and setting environment variables<br>
Testing the deployed app and ensuring it works as expected<br>
Updating the app with new features and improvements as needed<br>

https://user-images.githubusercontent.com/60037478/230733310-9b6bf171-14bc-4d9b-a5b5-2c0a084a4f85.mp4

![](ipl.gif)
