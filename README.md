# java-docker-app

After creating Dockerfile, we are changing working directory.

Inside directory, create an image by following the below command. 
we must login as root in order to create an image. 
In this example, we have switched to as a root user. In the following command, java-appis name of the image. We can have any name for our docker image.

=> docker build -t java-app . 

Checking image is created

=> docker images

Run Docker Image
After creating image successfully. Now we can run docker by using run command. The following command is used to run java-app.

=> docker run java-app  
