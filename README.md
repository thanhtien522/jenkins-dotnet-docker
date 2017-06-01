# jenkins-dotnet-docker

#Base On

## [jenkins](https://hub.docker.com/_/jenkins/)

#Useage
``
docker run --restart always --name jenkins \
-v $PWD/jenkins_home:/var/jenkins_home  \
-d -p 8080:8080 -p 50000:50000 daocloud.io/koukouge/jenkins-dotnet:1.0
``
