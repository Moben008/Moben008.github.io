# Moben008.github.io
#task: 
#Use a free account on Azure and GitHub and implement a basic deployment pipeline using 
#GitHub actions to create an Azure resource group and provision a Web App, a SQL Database, 
#one AutoScale settings, at least one Alert rules, and monitoring (App Insights). 
#Web App backend must be able to use that SQL database. 
#Deploy a simple Web App to this infrastructure from the pipeline (can be just a static html page)

#After creating an Azure account, I installed the Azure extension on VS code. 
#I created a new Respository called Moben008 in github
#On VS code I used React library to create an easy web application 
#After that I deployed the App on the github repository using Windows Powershall commad line
#After pushing the app to github, I created a new repository secret on giithub. 
#on Azure i used the bash command line to get the credentials needed so i can put them as a value in the repository secret
#The next step was to make a new workflow in github actions, and use the github action to create a Resource group on Azure
#You can find those instructions for the pipeline inside the YML file. 
#After that i created an SQL file on VS code with a table script.
#I went to Azure and I created a SQL server, and after that I made the db connection using github secret
#Unfortunaltly I received an Error, when i tried to build the SQL database on githb
#It was not able to find the credentails from Azure
#this is a link for the app https://blue-cliff-05556c103.1.azurestaticapps.net

