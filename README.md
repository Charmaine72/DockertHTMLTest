# A Simple Static Site test to make sure that I understand some of the fundermentals of Docker.
 #Created from a bootstrap template to speed the process up.
 #Steps that can be followed to test docker for yourself
 
 #Create a new directory 
 #Create a index.html file
 #Create a Docker file 
 #Edit docker file to include which webserver that can be used rather its nginx or apache
 #Build image docker build -t <webserver name>:<verision> .
  #Run image docker run -d -p 80:80 webserver-image:v1
#I like to check the the image is there and running - docker ps  or docker ps -a
  #Verify it worked by going to local host on you web browser by using localhost:<PORT>
