# Jenkins
## Why Jenkins?
### jenkins is used to solve problems like  
* Slower Releases
* Manual Builds
* Non repeatable processes
* No automation

### Jenkins Provides
* automated Builds
* automated tests
* Automated CI/CD pipelilines
* automated Deployments
* ability to install jenkins locally
* Jenkins Support and Plugins

## CI/CD

What is CI?
Contious Delivery is not equal to continous Deployment

## Why Jenkins
### Jenkins is used because
* Free
* all plugins are free
* support container,VM and Cloud
* Enterprise options are also available


## How to install Jenkins
* create EC2 instance or vm on local machine
* update the os
* steps to install jenkins: 
    * install Java
    * add package repository to the machine
    * install jenkins: yum install jenkins
    * start the service: sudo systemctl start jenkins
    * check the service status: sudo systemctl status jenkins
    * allow firewall for 8080 port
    * check firewall status
    * open the port in the network of the cloud, if jenkins is not accessible
* check the password at the file path  
    `sudo cat /var/lib/jenkins/secrets/initialAdminPassword`  
* 
