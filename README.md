# app-docker

Build do Projeto
dotnet publish --configuration Release --output dist
Criando imagem da aplicação
docker build -t aspnetcorewebapi/app1:1.0 .
Criando container da aplicação
docker container create -p 3000:80 --name webapi aspnetcorewebapi/app1:1.0