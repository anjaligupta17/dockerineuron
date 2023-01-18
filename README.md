# dockerineuron
docker pull imagename
docker run imagename
docker ps -a //for container view
docker rmi imagename //imageremove
docker rm containerid //containername
docker ps -a -q //all container
docker rm $(docker ps -a -q) //delete all container  
