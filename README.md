# Devops-Ubuntu-Jenkins

This repository contains a simple DevOps demonstration project showing how to build and deploy a basic web application using **Docker** and integrates it into a **Jenkins CI/CD workflow**. The goal of this project is to help beginners understand Docker containerization and how Jenkins can automate building and running Docker images based on code changes.

---

## 📌 Project Overview

This project includes:

✔ A simple static HTML website (index.html)  
✔ A Dockerfile to containerize the website using **Nginx**  
✔ A workflow that can be extended further with **Jenkins CI/CD**

---

## 🚀 Project Flow

1. **Write a basic web page**  
   We created a simple `index.html` file that displays a welcome message.

2. **Dockerize the Web App**  
   - A `Dockerfile` is written which:
     - Uses `nginx` as the base image
     - Copies the web page into the Nginx server directory
     - Exposes port 80

3. **Build the Docker image**  
   The Docker image is built locally using the Docker CLI.

4. **Run the Docker container**  
   After building the image, the container is launched and the web app is hosted locally.

5. **(Future) Jenkins Integration**  
   This repository is ready to plug into Jenkins for automatic building, testing, and deployment from GitHub changes.

---

## 🗂 Folder Structure



