# Udagram-Project
Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:

The Simple Frontend A basic Ionic client web application which consumes the RestAPI Backend.
The RestAPI Backend, a Node-Express server which can be deployed to a cloud service.
The Image Filtering Microservice, It is a Node-Express application which runs a simple script to process images

## Project Tasks Acomplished
- A new Node environment was setup
- A new endpoint that uses query parameter to download an image from a public URL, filter the image, and return the result was created.
- The application was deployed to Elastic Beanstalk using `eb init`, `eb create` and `eb deploy` cli commands

[endpoint url](http://udagram-jonah-dev-dev.us-east-1.elasticbeanstalk.com)
