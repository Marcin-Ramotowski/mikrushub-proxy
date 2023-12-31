# Mikrushub - nginx reverse proxy

It is my own website with the reverse proxy hosted on my own domain mikrushub.pl. It contains also docker-compose configurations to deploy some of known development services:
Gitea, Jenkins and Docker Registry with GUI in the Docker containers. I placed also nginx configuration to run reverse proxy on this website 
without bind ports containers to ports on the virtual machine. Traffic to the site is redirected directly to the container of the service with which we connect on individual subdomains.
I invite you to learn more about the project
