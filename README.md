# Mikrushub - Nginx reverse proxy - PL

To moja własna strona z reverse proxy hostowanym na mojej własnej domenie mikrushub.pl. Zawiera również konfiguracje docker-compose do wdrażania niektórych znanych usług programistycznych:
Gitea, Jenkins i Docker Registry z GUI w kontenerach Docker. Umieściłem również konfigurację nginx, aby uruchomić reverse proxy na tej stronie 
bez podpinania portów kontenerów do portów na maszynie wirtualnej. Ruch na stronie jest przekierowywany bezpośrednio do kontenera usługi, z którą łączymy się na poszczególnych subdomenach.
Zapraszam do zapoznania się z projektem.

# Mikrushub - Nginx reverse proxy - EN

It is my own website with the reverse proxy hosted on my own domain mikrushub.pl. It contains also docker-compose configurations to deploy some of known development services:
Gitea, Jenkins and Docker Registry with GUI in the Docker containers. I placed also nginx configuration to run reverse proxy on this website 
without bind ports containers to ports on the virtual machine. Traffic to the site is redirected directly to the container of the service with which we connect on individual subdomains.
I invite you to learn more about the project.
