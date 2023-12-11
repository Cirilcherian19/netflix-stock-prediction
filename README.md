#NETFLIX STOCK PREDICTION




#The art of forecasting stock prices has been a difficult task for many of the researchers and analysts. In fact, investors are highly interested in the research area of stock price prediction. For a good and successful investment, many investors are keen on knowing the future situation of the stock market. Good and effective prediction systems for the stock market help traders, investors, and analyst by providing supportive information like the future direction of the stock market.
The Dataset contains data for 5 years ie. from 5th Feb 2018 to 5th Feb 2022






HOW TO RUN?
1:create the environment using anaconda
using command in cmd:conda create -n cnncls python=3.9 -y     activate environment:conda activate 'environment name'




2:install the rquirements for the environment setup
using:pip install -r requirements.txt



3:finally run python application.py to run the complete code
NOW open up your local host and port check whether it is working fine..


workflow:

setup the github repository


creating new environment


setup setup.py and requirements.txt


creating .gitignore file


Run setup.py which will builds and create packages and reuirements


Build src as a package

under components data ingestion.py,data_transformation.py,modeltrainer.py are created for ingesting,transforming and training the model


create logger.py  for logging purpose 


create exception.py for custom exception



create utils.py for making functions that are frequently used in project


##Deployment of the project

deployed with python config,elastic beanstalk and cd pipeline


1:create the application from AWS console

2:create an environment for the application


3:create cd pipeline for transfering data from github to AWS environment..


4:execute pipeline for deploying the project




