# Nginx Fpm 
This docker image contains nginx, php-fpm , drush and composer. You can find it in Docker hub here [https://hub.docker.com/r/appsvcorg/nginx-fpm/](https://hub.docker.com/r/appsvcorg/nginx-fpm/)
It can run on both [Azure Web App on Linux](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-linux-intro) and your Docker engines's host.

# Docker Images for App Service Linux 
This repository contains docker images that are used for App Service Linux. Some images may be maintained by our team and some maintained by contirbutors.

# How to Deploy to Azure 
1. Create a Web App for Containers 
2. Update App Setting ```WEBSITES_ENABLE_APP_SERVICE_STORAGE``` = true 
>If the ```WEBSITES_ENABLE_APP_SERVICE_STORAGE``` setting is false, the /home/ directory will not be shared across scale instances, and files that are written there will not be persisted across restarts.
3. Browse https://[website]/index.php

