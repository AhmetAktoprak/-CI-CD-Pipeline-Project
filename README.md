# -CI-CD-Pipeline-Project


[![Python application test with Github Actions](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/actions/workflows/pythonapp.yml)


# Overview

<TODO: complete this with an overview of your project>

## Project Plan
<TODO: Project Plan

* [A link](https://trello.com/invite/b/14uKHOH7/ATTIbcf85a2df9fd65896c5d727a212c77e42F210F69/ci-cd-project) to a Trello board for the project
* [A link](https://docs.google.com/spreadsheets/d/1m_9LSaJEdbdkG3M6LbqqFDDpVbcVy23lVbyiAUpTmFk/edit?hl=tr&pli=1#gid=1348135932) to a spreadsheet that includes the original and final project plan>

## Instructions

* Architectural Diagram

   ![alt text](file:///C:/Users/Ahmet.Aktoprak/OneDrive%20-%20Shell/Documents/My%20Pictures/Screenshots/Project%20%20Diagram.png)

when the source code is pushed to Github, the GitHub Action is triggered for testing. In the meantime the Azure Pipeline is triggered for building the application and deplyong it to the Azure App Service.

## seting up Azure cloud shell:
 ### 1-Open Azure cloud shell
 ### 2-Generate a SHH Key and copy it to your Github Account

```
ssh-keygen -t rsa
cat ~/.ssh/id_rsa.pub
```
the genertaed ssh key should be add to the github account through Account settings then ssh and GPG key 

 ### 3-Clone the project from Github
 ![alt text]()

```
git clone git@github.com:AhmetAktoprak/CI-CD-Pipeline-Project.git
```
### make all 
 
## CI - CD
### git hub action test 
 
### Project running on Azure App Service

### link My Agent with the VM



### Successful deploy of the project in Azure Pipelines
 

 
### Running Azure App Service from Azure Pipelines automatic deployment
 


 ### locust log 



## Enhancements

make it in way that keep it an up to date project, in case someone tried to use it a year later will be able without facing issues 

## Demo 



