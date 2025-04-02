![image](https://github.com/user-attachments/assets/4dd83dea-8bf9-4d82-9875-4442935ae892)
This Project aims to predict wheter a given tweet id related to  a disaster or not using machine learning. The trained model is then deployed as a web applicationusing Flask, allowing users to input tweet and receive real time prediction.

Prerequisites 
------------------------------------------------------------------------------------------------------------------
Befire running the project, ensure you have the following dependencies Installed

Python (Verion 3.6 or heigher) PIP package manager Flask(pip install Falsk), scikit-learn (pip install sci-kit learn) pandas (pip install pandas)
* preprocess.py - Contains functions for text preprocessing and feature extraction.
* vectorize.py - Contains functions for text vectorization using CountVectorizer and TfidfVectorizer.
* train_model.py - Script to train the logistic regression model.
* predict.py - Script to make predictions using the trained model.
* logistic_regression_model.pkl - Serialized logistic regression model.
* README.md - This readme file.


Training the model
------------------------------------------------------------

To train the model, follow these steps:

Open and run the Jupyter notebook train_model.ipynb located in the notebooks/ directory. The notebook will load the dataset (data/disaster_tweets.csv), preprocess the data, train the model, and save it as app/model.pkl.

Running the Web App

To run the web application, follow these steps:

Navigate to the app/ directory. Run the Flask application using the following command: python app.py

Once the application is running, open a web browser and go to http://localhost:5000 to access the web interface.

Using the Web Interface

In the input field, enter the tweet text that you want to classify. Click the "Predict" button. The predicted class (disaster or not) will be displayed on the web page. Contributing If you would like to contribute to this project, feel free to submit a pull request.
