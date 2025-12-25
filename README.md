## CI/CD Pipeline Setup

## Objective
The objective of this project is to build a CI/CD pipeline using GitHub Actions.
The pipeline automatically runs whenever code is pushed to the main branch and performs build and deployment steps for a simple web application.

## Tools Used
GitHub
GitHub Actions
Visual Studio Code
HTML

## Project Description
In this project, a simple web application is created using HTML. A CI/CD pipeline is configured using GitHub Actions. Whenever a developer pushes code to the main branch, the pipeline is triggered automatically. The pipeline checks out the source code, runs a basic test step, and then performs a deployment step.

## CI/CD Workflow Steps

Developer pushes code to the main branch.

GitHub Actions workflow starts automatically.

The pipeline checks out the repository code.

A basic test step is executed.

The application deployment step runs automatically.

## Pipeline Execution Screenshots

### Initial Failure
During the initial execution, the pipeline failed due to a workflow configuration issue. The error was identified by checking the GitHub Actions logs. After correcting the workflow file, the issue was resolved.

### Pipeline Failed Screenshot
![Failed SS](https://raw.githubusercontent.com/Shravan96-Cloud/CI-CD-PIPELINE-SETUP/main/images/pipeline-failed.png)

### Successful Execution
After fixing the configuration issue, the pipeline ran successfully and completed all the steps without errors.

### Pipeline Success Screenshot
https://raw.github.com/Shravan96-Cloud/CI-CD-PIPELINE-SETUP/main/images/pipeline-success.png

Conclusion
This project successfully demonstrates a working CI/CD pipeline using GitHub Actions. The pipeline automates the process of building and deploying a web application, reducing manual effort and ensuring consistency in deployments.
