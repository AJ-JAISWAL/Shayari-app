# Shayari-App    

Welcome to the Shayari App! This is a simple application that generates and displays beautiful shayaris (poetic verses) for you. The app is containerized using Docker, making it easy to deploy and run in any environment.

## Table of Contents

- [Introduction](#Shayari-App)
- [Table of Contents](#table-of-contents)
- [Features](#Features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Support](#Support)

## Features
1. Random Shayari Generation: Get random shayaris on various topics.

2. Easy to Use: Simple and intuitive interface.

3. Dockerized: Ready-to-use Docker image for seamless deployment.

## Prerequisites

Before you begin, ensure you have the following installed:

Docker: Make sure Docker is installed on your system. You can download it from https://www.docker.com/get-started/.

Docker Compose (optional): If you want to use Docker Compose for easier management.

## Getting Started

Step 1: Pull the Docker Image
You can pull the pre-built Docker image from Docker Hub using the following command : <br>["docker pull <your-dockerhub-username>/shayari-app:latest"]

Replace <your-dockerhub-username> with your Docker Hub username or the repository name where the image is hosted.

Step 2: Run the Docker Container
Once the image is pulled, you can run the container using the following command : <br>["docker run -d -e GROK_API_KEY="your-secret-api-key" -p 8501:8501 <your-dockerhub-username>/shayari-app:latest"]

 -d: Runs the container in detached mode (in the background).
 -p 8501:8501: Maps port 8501 on your local machine to port 8501 in the container.

Step 3: Access the App
Open your web browser and navigate to :  [http://localhost:8501]

You should see the Shayari App up and running!

## Support

If you encounter any issues or have questions, please open an issue in the repository or contact me at [anantjaiswal2002@gmail.com].
