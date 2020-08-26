### **Devops Project**

This was a project created to learn more about Continuous Integration and Continuous Deployment. Github Link

This project consists of a basic website in a Github Repository. I use AWS to host 3 different virtual servers. The first instance hosts Jenkins. The second instance is the controller node. The third instance is a QA Server.

Jenkins is configured to pick up code from Github and build everytime there is a new commit in the github repository. (Coninuous Integration/Continuous Delivery) Deployment is taken care by Ansible. Code is deployed to a Docker container on a virtual QA Server using SSH.
