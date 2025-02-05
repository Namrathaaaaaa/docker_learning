# docker_learning

project runnning commands

Project3 
-> building an image 
docker  build -t my_nginx_image . 
-> If it throws error then 
docker system prune --all --force
->if the terminal shows error for running the code becoz of the port being already used by docker or other apps just change the port to 8090
In the terminal type : 
docker run -p 8080:80 --name container4 my_nginx_image (or)
docker run -p 8090:80 --name container4 my_nginx_image
-> write copy command for html path in dockerfile
Run the commands again 
docker build -t my_nginx_image . 
docker run -p 8090:80 my_nginx_image
-> when u refresh the page u get the output 


Project4\n
->docker build -t myflaskapp .\n
-> docker run -p 5001:5000 myflaskapp\n


Project5
-> docker build -t mynodeapp
-> docker run -p 3000:3000 mynodeapp


Project6
-> create a docker-compose.yml file 
-> compose up 
