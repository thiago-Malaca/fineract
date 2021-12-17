docker build -f ./Dockerfile . -t msfmicroserviceacr.azurecr.io/fineract

az acr login --name msfmicroserviceacr

docker push msfmicroserviceacr.azurecr.io/fineract