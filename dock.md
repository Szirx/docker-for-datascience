e51b2c08515a 

jupyter/scipy-notebook:e51b2c08515a 

docker exec -it e51b2c08515a  bash

docker cp wine.data e51b2c08515a:/home/jovyan/wine.data

docker run -p 10000:8888 jupyter/scipy-notebook:e51b2c08515a

docker run -v D:\dock:/home/jovyan/ -p 10000:8888 sha256:34137d8b396ca14cda1ceef4c44c4a7e28ee9659eca151e9b0d7f57d0c18b666  

docker build .