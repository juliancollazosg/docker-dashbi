
#creacion imagen
docker build -t dashbi:v10 .

#Ejecucion de la imagen
docker run -p 8050:8050 dashbi:v10


