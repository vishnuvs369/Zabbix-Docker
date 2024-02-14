# Zabbix 6.0 on Docker

=> Check docker and docker-compose installed or not
   
     docker version
     docker-compose version

   if not then install it.



=> Get docker compose file from GIT 'zabbix-Docker'   
   for that just clone the Repo



=> Create required volume mount path in server


=> Make required changes in compose file based on your requirement


=> check whether any container running on the port you mentioned
    
    docker ps



=> start docker compose
   
    docker-compose up -d     



=> checker docker is UP or NOT [docke ps]


=>  check the URL for zabbix

http://yourIP:8090



REF:-
* https://www.zabbix.com/documentation/6.0/en/manual/installation/containers
