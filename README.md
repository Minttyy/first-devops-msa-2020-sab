# MSA DevOps Project

This is where a build pipeline, release pipeline and a deployed website are needed from Azure to complete Phase 1 of MSA

## Azure Build Pipeline

There is a continuous deployment which creates releases when new commits are made in either develop or master branches

The following is what will occur: 
* Node is installed first
* We switch to the appropriate folder to use npm install and build
* Files are archived into zip files so they can be publish as artifacts
* Build Artifacts are used in the release pipeline to deploy the web app

## Azure Release Pipeline

There is a continuous deployment to deploy the release to Azure only when new commits occur in the master branch

## Deployed Website 

The URL is: https://msa-2020-devops-submission-sab.azurewebsites.net/

### Author: Sabrina Teoh


