# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-frontend)
A basic Ionic client web application which consumes the RestAPI Backend. [Covered in the course]
2. [The RestAPI Backend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-restapi), a Node-Express server which can be deployed to a cloud service. [Covered in the course]
3. [The Image Filtering Microservice](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code), the final project for the course. It is a Node-Express application which runs a simple script to process images. [Your assignment]

### Run the application on AWS
Application can be accessed at the endpoint: 
http://citrusudagram.ca-central-1.elasticbeanstalk.com/

e.g: http://citrusudagram.ca-central-1.elasticbeanstalk.com/filteredimage?image_url=https://placekitten.com/408/287

### Run the application locally
1. Clone the branch or download the zip
2. cd into citrus-udagram-master
3. npm install
4. npm run dev