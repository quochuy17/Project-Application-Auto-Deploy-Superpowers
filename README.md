# Project : Give Your Application Auto-Deploy Superpowers
Generally, in this project, the core mission is just to demonstrate the mastery of the following learning objectives (or sections) in this project including:
  + Describe the principles of CI/CD and its advantages for achieving, creating, and deploying automation for cloud-based software applications.
  + Design and construct CI/CD pipelines that support Continuous Delivery procedures using deployment strategies.
  + Deployment to cloud-based servers should be accomplished using a configuration management solution.
  + Use centralized structured logging to identify critical server issues for diagnosis.

## Project's intructions
In general, some intructions that are mandatory in this project including:
    1. Selling CI/CD
    2. Getting Started
    3. Deploying Working, Trustworthy Software
    4. Configuration Management
    5. Turn Errors into Sirens

## Project configurations
In this project, there are some softwares and technologies that can be used including:
  + Visual Studio Code, Git Hub
  + Circle CI, Ansible
  + Git bash

# Project's target
+ Firstly, just explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
+ Secondly, use deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
+ Third, utilize a configuration management tool to accomplish deployment to cloud-based servers.
+ Fourth, surface critical server errors for diagnosis using centralized structured logging.

### Project's Files included:
In this project, there are some essential files in order to implement including:
    + .circleci which stored "cloudfront.yml", "backend.yml" and "frontend.yml" file
    + Ansible Playbooks and Roles 
    + CircleCI config.yml file

### Project's Prerequisites
There are some main Prerequisites before starting to do this project including:
    + Initially, installed Git 
    + Second, SSH client like OpenSSH. Linux/Mac users can use the default terminal.
    + Third, NodeJs v13.8 and NPM v6.XX. If you already have another NodeJS installed, refer to this thread on Changing the NodeJS version using Node version manager (nvm).
    + Fourth, be clear about the directory structure relevant for the project:
      ├── .circleci 
      │   ├── ansible
      │   └── files
      ├── backend  
      │   ├── src
      │   └── test
      ├── frontend 
      │   ├── src
      │   └── types
      └── util    # Files relevant for the running the app locally

## Project's main features
** SECTION 1: in this section, just prepare for implementing this project like environment on the local and be clear about all the project's prerequisites.

** SECTION 2: Utilize Deployment Strategies to Design and Build CI/CD Pipelines that Support Continuous Delivery Processes.
    + Set up CircleCI: complete ".circleci/config.yml" file.
    + Build Phase : compile/lint the source code to check for syntax errors or unintentional typos in code.
    + Test Phase : just build some Unit tests.
    + Analyze Phase : just develop a job that checks for known vulnerabilities every time we check in new code.
    + Alerts : add an alert so that botched builds raise a nice wavy red flag.
        
** SECTION 3: utilize a Configuration Management Tool to Accomplish Deployment to Cloud-Based Servers
    + Setup : some AWS services and CloudFront Distribution Primer and CircleCI.
    + Infrastructure Phase : 
        . Create the Infrastructure
        . Configure Infrastructure
    + Deploy Phase : 
        . Database Migrations
        . Deploy Frontend
        . Deploy Backend
    + Smoke Test Phase 
    + Rollback Phase
    + Promotion Phase
    + Cleanup Phase
    + Then, when above phase run successfully, just run the application for examining.

** SECTION 4: Surface Critical Server Errors for Diagnosis Using Centralized Logging
    + Setup - Prometheus Server in AWS EC2 : Setup Back-End Monitoring
    + Setup Alerts
        . Add SSH into your Prometheus Server.
        . Install and configure AlertManager.
        . Set up an alert for low memory, or instance down, or any other condition that controls to intentionally cause an alert.
        . Then, take some required screenshots which are in the Project Rubric.

## Project Submission
There are some mandatory files and other features when submitting this project including:
    - A text file named urls.txt including:
      + Public Url to GitHub repository (not private) [URL01]
      + Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]

    - The screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder. 
      + Job failed because of compile errors. [SCREENSHOT01]
      + Job failed because of unit tests. [SCREENSHOT02]
      + Job that failed because of vulnerable packages. [SCREENSHOT03]
      + An alert from one of your failed builds. [SCREENSHOT04]
      + Appropriate job failure for infrastructure creation. [SCREENSHOT05]
      + Appropriate job failure for the smoke test job. [SCREENSHOT06]
      + Successful rollback after a failed smoke test. [SCREENSHOT07]
      + Successful promotion job. [SCREENSHOT08]
      + Successful cleanup job. [SCREENSHOT09]
      + Only deploy on pushed to master branch. [SCREENSHOT10]
      + Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11]
      + Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12]
      + Provide a screenshot showing the evidence of deployed and functioning front-end application in CloudFront (aka, your production front-end). [URL03_SCREENSHOT]
      + Provide a screenshot showing the evidence of a healthy backend application. The backend endpoint status should show a healthy response. [URL04_SCREENSHOT]
      + Provide a screenshot of your Prometheus server showing UP state [URL05_SCREENSHOT]
      
    - The presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder.



 
