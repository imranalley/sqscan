# sqscan

https://hub.docker.com/_/sonarqube

docker pull sonarqube

https://docs.sonarqube.org/latest/setup/get-started-2-minutes/

docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest
