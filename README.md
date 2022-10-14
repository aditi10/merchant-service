The application can be built using  a Dockerfile 

To build the application 
docker build -t merchant .
docker tag merchant 10112018/merchant:latest
docker push 10112018/merchant:latest

Once the application is built push it to Dockerhub or any repository
