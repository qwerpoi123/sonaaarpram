version: '3.7'
services:
  jenkins:
    image: jenkins-sonar:latest
    privileged: true
    user: root
    ports:
      - 9000:9000
      - 9092:9092
    container_name: sonarqube
    
