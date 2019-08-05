# Supported tags and respective Dockerfile links

* `latest`

# Contents

* Container built on top of jenkins/jenkins:lts with [miniconda3](https://conda.io/miniconda.html) and ansible

## Tips to start the Container

###### Starting jupyter notebook without Password or Token

```
docker run --name integrated-automation -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home marcoan/integrated-automation
```

# Integrated Automation

- Users need to log to multiple systems and environments to perform daily basis repetitive tasks.
- Scheduled tasks need to be scheduled on each system and environment.
- Time consuming tasks being executed in several servers and environments.
- Too much time wasted debugging decentralized manual and scheduled tasks.
- Automation scripts were already old as soon as they were done.
- Hard to implement and maintain.
- Each user have a different version in their computer

# Objective

Centralize and automate daily and repetitive tasks in an integrated environment.

![](https://cdn.freebiesupply.com/logos/thumbs/2x/jenkins-1-logo.png)

- Front end integration for user and scheduled tasks.  
- Backend for simple tasks

![](https://cdn.swapps.com/uploads/2018/02/ansible-header-1024x640-1280x720.png)

- Backend to perform the tasks in every systems and environments
