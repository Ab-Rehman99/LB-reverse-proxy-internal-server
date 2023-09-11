Security Layers: LB, Reverse Proxy, and Internal servers

Reverse Proxy is acting as middle layer between Load balancer and Internal servers. The request from www.example.com goes to load balancer and it will forward it to reverse proxy (Nginx servers). The Nginx server will then forward the request to Internal servers (apache2 servers) where the actual application will reside.
