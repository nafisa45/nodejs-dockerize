# nodejs-dockerize
1.docker build -t node-devto .
2.docker run -v /home/hp/node-docker-app:/app -p4000:3000 -d --name node-api-devto node-devto
in case of /home/hp/node-docker-app use ur project path.
then click the port from docker desktop.it will show the updated code each time.
or u can run 
docker-compose up
