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

   ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/Project%20%20Diagram.png)

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
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/git%20clone.png)

```
git clone https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project.git
```
### make all 
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/make%20all%20passed.png)

 ### Prediction
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/prediction.png)

## CI - CD
### git hub action test 
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/github%20actions.png)

### Project running on Azure App Service
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/webapp%20page.png)

### link My Agent with the VM
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/my%20agent.png)


### Successful deploy of the project in Azure Pipelines
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/pipeline.png)


### Running Azure App Service from Azure Pipelines automatic deployment
 ![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/pipeline%20screen.png)


 ### locust log 
![alt text](https://github.com/AhmetAktoprak/CI-CD-Pipeline-Project/blob/main/locust%20log.png)



## Enhancements

make it in way that keep it an up to date project, in case someone tried to use it a year later will be able without facing issues 

## Demo 

[A Link](https://youtu.be/HCBGQdPL3tY?si=fHM8ZdYU4hLCMLBp) to Screencast on YouTube   
