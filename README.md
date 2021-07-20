# Future-Accidents

The project is submitted for a challenge for the Digital Product School (DPS). In the project a dataframe consisting of historical values of the accidents from different categories in the city of Munich, Germany.

 The outcomes of the project:
 - Cleaning the data,  visualizing the historical accidents from the dataframe
 - Training a model to forecast future values.
 - Deploying the model with an endpoint that accepts POST requests in JSON body.


### Files

 - **Preprocessing.ipynb**: A jupyter notebook contains a step-by-step of importing the data, cleaning, and then visualizing the results
 - **Training.ipynb**: A jupyter notebook that loads the preprocessed data, then estimating the parameters passed for the forecasting algorithm "SARIMA". The model is trained and tested on the year 2020 data, the model is then evaluated and exported for deployment.
 - **inference.py & endpoint.py**: Two scripts, in order, the former contains the class which performs the  forecasting and returns the result. The latter is the endpoint, which is deployed.
 - **test.py**: a script to test the requests to the endpoint.
