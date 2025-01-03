# First commit to Blog-API

## Local development
using docker-compose command you can run it locally
```
docker-compose run .
```

```
docker run -it --rm -e FirebaseCredentialsPath=<someconfigurationValue> <image-name> -p 5000:8080
```
> Here 5000 being localhost , 8080 being the port exposed from docker file

## Creating Infra
> this creates Infra on Azure
- go into the terraform directory by doing cd /path/to/terraform
run below command to create the infra
```
terraform init
```
- then you can run below cmd for creating it.
```
terraform apply
```
