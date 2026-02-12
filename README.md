# -cd-jenkins-docker-compose-ec2
Deploy to EC2 server from Jenkins Pipeline -CI/CD part 2

technologies used:
AWS, Jenkins, Docker, Linux, Git, Java, Maven, Docker Hub

Projekt description:
- Install Docker compose on AWS ECS instance
- create docker-compose-yaml file that deploys our web application image
- configure jenkins pipeline to deploy newly built image using Docker compose on EC2 server
- Improvement: extract multiple linux commands that are executed on remote server into a separate shell script and execute the script from Jenkinsfile
  
