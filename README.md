# Jenkins CI/CD Pipeline

## Obective

the main aim of this task is to create a simple Jenkins pipeline that can automatically build, test, and deploy an application.

 **Tools Used**

 - Jenkins
 - Docker
 - GitHub
 - GitHub Codespaces

 **Pipeline Stages**

 The Jenkins pipeline has three basic stages:

 1. **Build** - Builds the application.
 2. **Test** - Checks the application.
 3. **Deploy** - Deploys the application using   Docker.

 **What I Did**

 I created a simple web application and used Github Codespaces to work on the project. I created a Dockerfile to run the application in a Docker container and a Jenkinsfile to define the CI/CD pipeline.

 The Jenkinsfile contains three stages: Build, Test, and Deploy.

 ## Projectr Structure

 jenkins-cicd/
 - app/
   - index.html/
 - Dockerfile/
 - Jenkinsfile/
 - README.md

 ## What I Learn

 I learned the basics of Jenkins CI/CD pipelines, Docker, and how Jenkins can be used to automate the build, testing, and deployment process.

## Pipeline Result

The Jenkins pipeline was successfully executed with the following stages:

- Build - Docker image was successfully created.
- Test - Docker image was verified.
- Deploy - Application was successfully deployed in a Docker container.

The pipeline completed with **SUCCESS** status.
 




