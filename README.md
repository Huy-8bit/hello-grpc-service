# User Authentication Services 

This is a project built with the following requirements:
 - Call to "user profile service" check user is active or not
 - Create access token for user and save information to redis


## Getting started

To get started with this project, follow the steps below.

## Requirements and configuration
- Golang 1.21
- Docker
- Docker-compose
- MongoDB 


## Clone the repository

```
cd your_folder
git clone https://gitlab.vnpaycloud.vn/cloud/training/by-user/huyng2/userauthsystem.git
git checkout dev
```



## Run with docker compose
```
docker-compose up -d
```
project will run on http://localhost:50052


## Run with golang

```
go mod tidy
go run main.go

```




# hello-grpc-service
