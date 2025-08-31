# This readme outlines the steps and approach I took to containerize the given app and deploy into Kubernetes cluster using Minikube.
# This repo contains Dockerfile and docker-compose.yml file used to dockerize the app. Also I have attached the relevant screenshots.

Below is the approach I took.
1) Installed Docker as Minikube runs inside Docker.
2) Installed Minikube in my Ubuntu24.04 WSL. Version installed: v1.36.0
3) Installed Kubectl for CLI. Client Version: v1.30.0
4) Below shows screenshots of pods and services deployed on Minikube cluster.
![alt text](image.png)
5) ![alt text](image-1.png)
6) Screenshot showing mongodb as container
![alt text](image-2.png)
7) Screenshot showing entries made by Venkat on UI screen. I added few comments.
![alt text](image-3.png)
8) Below shows UI screen of the application.
![alt text](image-4.png)
9) DockerHub showing the image pushed.
![alt text](image-5.png)



# Swimlane DevOps Practical

This is a demo application to use for working on the Swimlane DevOps hiring practical project.

### Install

Required environment variables:
- `MONGODB_URL` - Full MongoDB connection URI to connect to

### Testing Locally
```sh
git clone git://github.com/swimlane/devops-practical.git
npm install
cp .env.example .env
npm start
```

Then visit [http://localhost:3000/](http://localhost:3000/)# devops-practical-1
