
ML-Model-Flask-NBA Players:

Project Structure:

This project has four major parts :

model.ipynb : This contains code for our Machine Learning model to predict Target_5years based on training data in 'nba-logreg.csv' file.

serveur.ipynb : This contains Flask APIs that receives players details through API calls, computes the precited value based on our model and returns it.

request.ipynb : This uses requests module to call APIs already defined in app.py and dispalys the returned value.

templates : This folder contains the HTML template to allow user to enter players detail and displays the predicted target-5years.

Static/css: for web page style 


Running the project:

Ensure that you are in the project home directory. Create the machine learning model by running: model.ipynb

This would create a serialized version of our model into a file model.pkl

Run serveur.ipynb  to start Flask API

By default, flask will run on port 5000.

Enter valid float values in all 16 input boxes and hit Predict.

If everything goes well, you should be able to see the predcited target vaule on the HTML page!

Thank you !





