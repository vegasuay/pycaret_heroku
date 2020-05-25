# Proyect 
Build and deploy your first machine learning web app


## PyCaret

PyCaret is an open source, low-code machine learning library in Python to train and deploy machine learning pipelines and models in production. PyCaret can be installed easily using pip.

### - for Jupyter notebook on your local computer
```python
pip install pycaret
```

## Flask

Flask is a framework that allows you to build web applications. A web application can be a commercial website, a blog, e-commerce system, or an application that generates predictions from data provided in real-time using trained models. If you don’t have Flask installed, you can use pip to install it.

### - Install Flask
```python
pip install Flask
```

### - Test App
```python
python app.py
```

## GitHub

GitHub is a cloud-based service that is used to host, manage and control code. Imagine you are working in a large team where multiple people (sometime hundreds of them) are making changes. PyCaret is itself an example of an open-source project where hundreds of community developers are continuously contributing to source code. If you haven’t used GitHub before, you can sign up for a free account.

## Heroku

Heroku is a platform as a service (PaaS) that enables the deployment of web apps based on a managed container system, with integrated data services and a powerful ecosystem. In simple words, this will allow you to take the application from your local machine to the cloud so that anybody can access it using a Web URL. In this tutorial we have chosen Heroku for deployment as it provides free resource hours when you sign up for new account.

## Requirements
```
pycaret==1.0.0
Flask==1.1.1
Jinja2==2.10.1
gunicorn==19.9.0
certifi==2019.11.28
itsdangerous==1.1.0
```
# Business Problem
 
An insurance company wants to improve its cash flow forecasting by better predicting patient charges using demographic and basic patient health risk metrics at the time of hospitalization.

data source: https://www.kaggle.com/mirichoi0218/insurance#insurance.csv

# Deploy the Web App on Heroku
Now that the model is trained, the machine learning pipeline is ready, and the application is tested on our local machine, we are ready to start our deployment on Heroku. There are couple of ways to upload your application source code onto Heroku. The simplest way is to link a GitHub repository to your Heroku account.

By now you are familiar with all the files in repository shown above except for two files i.e. ‘requirements.txt’ and ‘Procfile’.