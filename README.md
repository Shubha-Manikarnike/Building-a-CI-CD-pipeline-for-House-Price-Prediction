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
 
 * Project cloned into Azure Cloud Shell
 
![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Project_CLoned%20in%20Azure%20Cloud%20Shell.jpg)


* Project running on Azure App Service

![image](https://user-images.githubusercontent.com/14934998/195813554-47076d9c-6c68-4e18-b691-be8f24a1a0ef.png)

![image](https://user-images.githubusercontent.com/14934998/195813828-2149980c-1268-4a49-b6e0-663861ce45de.png)

* Passing tests that are displayed after running the `make all` command from the `Makefile`

![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/Successful%20make_all.jpg)

![image](https://user-images.githubusercontent.com/14934998/195814730-b8c98db4-53be-4fdb-bd24-c1612c9a696a.png)


* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

![image](https://github.com/Shubha-Manikarnike/Building-a-CI-CD-pipeline-for-House-Price-Prediction/blob/main/img/CICI-Completed.jpg)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

![image](https://user-images.githubusercontent.com/14934998/195814449-5ca4e9c3-4929-4389-a874-44f7506b1e10.png)

* 
## Enhancements

* The library dependecies need to be checked correctly to ensure that the project works seemlessly.
* The webpage can be enhanced to read inputs from the webpage itself and predict the output on the webpage itself.

## Demo 

<TODO: Add link Screencast on YouTube>


