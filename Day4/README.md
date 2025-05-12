# Day 4: Nginx Reverse Proxy

## Overview

On Day 4 of my **Azure 100 Days Challenge**, I learned about setting up a **Node.js application** and configuring **Nginx** as a **reverse proxy**. In this exercise, I deployed a basic Node.js app and set up Nginx to handle HTTP requests and forward them to the Node.js application.

## Key Learnings

- **What is a Reverse Proxy?**
  - A reverse proxy is a server that sits between clients and a backend server (in this case, a Node.js app). It handles client requests and forwards them to the backend server.
  - Nginx is commonly used as a reverse proxy to distribute traffic and enhance security.

- **Setting up Nginx on Ubuntu:**
  - I installed Nginx on an Ubuntu server using the `apt-get` package manager.
  - I created a custom configuration file for Nginx to set up a reverse proxy.

- **Node.js Application Setup:**
  - I created a basic Node.js application (`app.js`) that listens for incoming HTTP requests and sends a response.

- **Nginx Configuration:**
  - In the `nginx.conf` file, I set up Nginx to listen on port 80 and forward requests to the Node.js app running on a different port (e.g., port 3000).

- **Testing the Setup:**
  - I tested the setup using `curl` to make sure Nginx was properly forwarding the requests to the Node.js application.
  - I also checked the setup in the browser by accessing the public IP of my Azure VM.

## Commands Used

- Install Nginx:

  ```bash
  sudo apt-get install nginx
