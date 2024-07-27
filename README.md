# QEATS

QEats is an app that makes food ordering convenient for millions of users. With just a few taps on their phone, users can relish their favorite food from nearby restaurants.


<br>


The app is not usable yet as the backend features are only partially implemented at the moment.


<br>


QEats is counting on you to build all the necessary backend features to make the end-to-end app functional for users. To build the app, you will focus on implementing product features in each part shown in the following QEats architecture diagram:


![alt text](image.png)

Objective
Support different frontend clients with the QEats backend server.


Focus Area

![alt text](image-1.png)


What's included: 
1. Gradle file created from start.spring.io
2. Plugins for Spotbugs, Checkstyle and Jacoco included
3. Other dependencies like Mongo, MySql and redis.
4. Dockerfile to start mongo server and run the spring boot application within.

###Usage - 

1. To build the repository - 

From the repository root, 

1. run `./gradlew build test`run the build
2. run `./gradlew bootjar` to create executable jar. The jar will be located inside build directories.

To run inside docker container, use below commands

To build docker image, use the command below - `docker build -t your_tag_name  .`

To run the generated container, use this command - `docker run -p8080:8080 your_tag_name`. This will run the server on 8080 port.. You can change the ports as per your needs. 


License - 
While this repository is licensed under APACHE 2.0 license, It is mandatory for users to share the readme.md and License file along with the changes they do in the contents.