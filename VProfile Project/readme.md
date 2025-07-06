# VProfile Project
## About the project 
- Multi Tier Web Application Stack
- Setup locally

  ### Scenario
  Working on project which has varieties of services that power the project runtime, also have a runbook/ setup document.

  ### Problem
  - Not comfortable in making changes in real servers
  - Local setup is complex
  - Time consuming
  - Non repeatable

  ### Solution
  Local setup that is automated, repeatable because of IAAC

  ## Tools
 -  Hypervisor : Oracle VM Virtual box
  - Automation : Vagrant
  - CLI : Git Bash
  - IDE : VS Code

  ### Objective
  - VM automation locally
  - Real world project setup locally

  ## Architecture Of Project Services
  - Nginx
  - Tomcat
  - Rabbitmq
  - Memcached
  - MYSQL

  ## Architecture Of Automated Setup
 -  Vagrant
  - VirtualBox
  - Git Bash

 User will enter ip add in browser of load balancer, we are using nginx web service to create load balancer, which will route req to tomcat server, user will login and data will be stored in mysql.RabbitMQ used as message broker. 
![Tomcat Screenshot 1](Screenshot%202025-07-07%20005311.png)

 ### Flow
 1. Setup tools
 2. Clone sc
 3. cd into vagrant dir
 4. bring up vms
 5. validate
 6. setup all services - Mysql, Memcached, Rabbit MQ, Tomcat, Nginx, App Build and Deploy
 7. Verify from browser
