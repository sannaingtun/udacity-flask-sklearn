# Overview

Building a CI/CD Pipeline to deploy package to Azure WebApp using Azure Pipeline and GitHub Repository

## Project Plan

- [Trello board for the project](https://trello.com/b/IyE8zLp5/udacity-project)
- [Spreadsheet](/project-management.xlsx)

## Instructions

- Architectural Diagram(Shows how key parts of the system work)
  ![Architecture](/Screenshots/architecture.png)

<TODO: Instructions for running the Python project. How could a user with no context run this project without asking you for any help. Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

- Project running on Azure App Service
  [Open this URL](https://flask-sklearn-san.azurewebsites.net/)
  ![Running WebApp](/Screenshots/webapp-running.png)
- Project cloned into Azure Cloud Shell
  ![Clone repo](/Screenshots/clone-cloud-shell.png)
- Passing tests that are displayed after running the `make all` command from the `Makefile`
  ![Make all](/Screenshots/make-all-1.png)
  ![Test Result](/Screenshots/make-all-2.png)
- Output of a test run
  ![Test run output](/Screenshots/github-test-pass-on-readme.png)
- Successful deploy of the project in Azure Pipelines. [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).
  ![Deployment Result](/Screenshots/pipeline-result-list.png)

- Running Azure App Service from Azure Pipelines automatic deployment
  ![Running App Service](/Screenshots/running-app-service.png)

- Successful prediction from deployed flask app in Azure Cloud Shell. [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
  ![Prediction Result](/Screenshots/make-predict.png)
  The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

- Output of streamed log files from deployed application
  [Log File](/Logs/2022_09_20_lw0sdlwk0001TB_default_docker.log)
  >

## Enhancements

- Need to modify API to be accessible from the App like Postman instead of running script

## Demo

![Demo Video](/Screenshots/Demo.mp4)
