# CTF Hackademics #2

Vous trouverez ici un export du container Docker du deuxième CTF Hackademics. 
Plus d'infos : https://hackademics.fr/forum/ctf/76485-r%C3%A9sultats-deuxi%C3%A8me-ctf-hackademics

## Utilisation 

Téléchargez l'export : https://github.com/HackademicsForum/hk-ctf-2/releases
Lancez les commandes suivantes :
````
docker load < ctf-hk-2.tar 
docker run -d ctf-hk-2 /bin/sh -c "/root/start.sh && tail -f /dev/null"
docker ps 
# Récupérer l'id du container 
docker inspect <container id> | grep "IPAddress"
````
Les ports 80 et 22 sont utilisés par ce container...

## Solution 

Lien de la solution : https://hackademics.fr/forum/ctf/76485-r%C3%A9sultats-deuxi%C3%A8me-ctf-hackademics?p=76573#post76573
