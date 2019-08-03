# Supported tags and respective Dockerfile links

* `latest`

# Contents

* Container built on top of jenkins/jenkins:lts with [miniconda3](https://conda.io/miniconda.html) and ansible

## Tips to start the Container

###### Starting jupyter notebook without Password or Token

```
docker run --name integrated-automation -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home marcoan/integrated-automation
```
