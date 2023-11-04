
#creacion imagen
docker build -t dashbi:v1 .

#Ejecucion de la imagen uodateDJBA
docker run -p 8050:8050 dashbi:v1


