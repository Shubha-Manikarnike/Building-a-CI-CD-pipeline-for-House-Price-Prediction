# Overview

This project demonstrates building a Github repository from scratch and create a scaffolding that will assist in performing both Continuous Integration and Continuous Delivery. Github Actions are used along with a Makefile, requirements.txt and application code to perform an initial lint, test, and install cycle. This project is integrated with Azure Pipelines to enable Continuous Delivery to Azure App Service.

The project comprises of the following steps:
1. Prepare a Project plan 
2. An architectural diagram.
3. Implement CI in github
4. Create and activate Azure Webapp
4. Deploy the Project in Azure Pipelines



## Project Plan


* A link to a Trello board for the project can be found here - [trello board](https://trello.com/b/EuHOoYu1/azure-data-engineering) 
* A link to a spreadsheet that includes the original and final project plan - [here](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/project%20plan/project-management-template%20for%20Azure%20Data%20Engineering.xlsx)

## Instructions

* Architectural Diagram (Shows how key parts of the system work)>

 ![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/cd-diagram.png)

* Project running on Azure App Service
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Webapp%20server%20deployes.jpg)
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Webapp%20server%20deployed1.jpg)

* Project cloned into Azure Cloud Shell
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Project_CLoned%20in%20Azure%20Cloud%20Shell.jpg)

* Passing tests that are displayed after running the `make all` command from the `Makefile`
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Successful%20make_all.jpg)

* Output of a test run
![image]()

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).


* Running Azure App Service from Azure Pipelines automatic deployment
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/CICI-Completed.jpg)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* 
## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


