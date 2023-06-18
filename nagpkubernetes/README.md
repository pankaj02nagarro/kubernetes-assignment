# Deploying .Net Microservices 


### Shopping MVC Client Application
First of all, we are going to develop Shopping MVC Client Application For Consuming Api Resource which will be the Shopping.Client Asp.Net MVC Web Project. But we will start with developing this project as a standalone Web application which includes own data inside it. And we will add container support with DockerFile, push docker images to Docker hub.
### Shopping API Application
After that we are going to develop Shopping.API Microservice with MongoDb and Compose All Docker Containers.
This API project will have Products data and performs CRUD operations with exposing api methods for consuming from Shopping Client project.

### Mongo Db
Our API project will manage product records stored in a no-sql mongodb database as described in the picture.
we will pull mongodb docker image from docker hub and create connection with our API project.
At the end of the section, we will have 3 microservices whichs are Shopping.Client — Shopping.API — MongoDb microservices.

### Docker hub Image path url

ShoppingAPI:-     https://hub.docker.com/r/pankaj02nagarro/shoppingapi
ShoppingClient:-  https://hub.docker.com/r/pankaj02nagarro/shoppingclient
MongoDb:-         https://hub.docker.com/_/mongo


API URL:-         http://localhost:31000/swagger/index.html  

Github Repository URL:- 