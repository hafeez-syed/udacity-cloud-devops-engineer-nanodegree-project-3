# Udacity Cloud Devops Nanodegree
## Project 3 - Jenkins Pipeline on AWS

This project consist of an HTML file with some content. The task is to create a pipeline in Jenkins that should trigger a build as when we commit the changes to the github repository


## Jenkins installation in Ubuntu (this works)
```bash
$ wget -q -O - https://jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -

$ sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list'

$ sudo apt-get update

$ sudo apt-get install jenkins
```