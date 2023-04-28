# Stock-Prediction-Web-App

This app created for my FYP project and it able to shows you the adjusted 
closing stock prices for a few different technology companies and predict 
the closing price for today.

### Running the App

Before you can run the web app, you need to first train the machine learning
models (should take less than a minute). If you do not train the models first,
the app.py script will error out. Running this script will train a machine
learning model for each of the companies and save the model and StandardScaler
object into a models folder in the current working directory.

```
python train_models.py
```

After training the models, you need to run the dash_app.py script and navigate
to the url shown in the terminal.

```
python app.py
```
