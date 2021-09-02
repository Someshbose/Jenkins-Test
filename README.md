# Jenkins-Test

To run Jenkins docker image run this command.
```sh
docker run -p 8088:8080 --name=jenkins-master jenkins/jenkins
```

To copy the 1st time password.
```sh
 docker exec 528683ce54ea cat /var/jenkins_home/secrets/initialAdminPassword
```
