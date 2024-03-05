# sample-python-app  
   
#Build    
$docker build -t sample-nodejs-app .     
$docker images    
$docker tag "sample-nodejs-app:latest" "your_username/sample-nodejs-app:latest"   


#Ship    
$docker login    
$docker push your_username/sample-nodejs-app:latest
Verify in Dockerhub    
   
#Run    
$docker container run -d --name c1 -p 80:8080 your_username/sample-nodejs-app   
$docker ps 

