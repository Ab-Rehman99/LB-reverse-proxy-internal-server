# LB-reverse-proxy-internal-server

Reverse Proxy is acting as middle layer between Load balancer and Internal servers. The request from www.example.com goes to load balancer and it will forward it to reverse proxy (Nginx servers). The Nginx server will then forward the request to Internal servers (apache2 servers) where the actual application will reside.

# Architecture:


![Screenshot 2023-09-11 131453](https://github.com/Ab-Rehman99/LB-reverse-proxy-internal-server/assets/85974328/221f3e09-ad1f-4a57-b988-24ecda3f87c1)

# Ngnix configuration Example:

![Ngnix Configuration Example](https://github.com/Ab-Rehman99/LB-reverse-proxy-internal-server/assets/85974328/894db19e-d9e6-42dd-a6e7-1249e5782ac3)

