## MA Online YouTube Video Downloader - Docker Compose YML File

## Overview
Do you want to create and run Docker Compose YML File?

Docker Compose is a tool for defining and running multi-container Docker applications. 
It allows developers to define the application’s services, networks, and volumes in a single file called a docker-compose.yml file. 
The docker-compose.yml file can be used to set up, configure, and start all of the services required for an application with a single command.

## Tools Used

- Docker Desktop
- VS Code


## How to Download

Download this project from here

https://github.com/ma-muhammadali/pse_MAOnlineYouTubeVideoDownloader_Docker_Compose_YML.git

## Requirements

## How to Create Docker Image

- Go to Docker Hub website and create your account (If not already created) https://hub.docker.com/

- After creating account on Docker Hub, please download and install Docker Desktop software on your machine. https://www.docker.com/products/docker-desktop/

- After installing Docker Desktop software, please run it and login into Docker Desktop using your account credentials created on Docker Hub.

- Download and Install Visual Studio Code (Windows Version) software from below URL. https://code.visualstudio.com/download

- Download MAOnlineYouTubeVideoDownloader_Docker_Compose_YML folder from GitHub repository and place it in VS Code workspace.

- Open MAOnlineYouTubeVideoDownloader_Docker_Compose_YML in VS Code

- After selecting the Terminal as Bash, check the YML file by running below command
	$ docker-compose config
	
	If there is no issue with .yml file than it will be displayed successfully. Otherwise, an error message will appear.

- Now we will create Docker-Compose Image by running below command.
	
	$ docker-compose up -d --d: detach mode
	
	In this command, we will build a Docker image and run the container

- When Docker Container is creared, it will start running automatically.

## Usage

* After running Docker Image Container python terminal/ Docker Desktop and then goto http://localhost:3000/
* Paste a youtube video url and click Start
* Click Download Video, Download will start automatically
