TACO SHOP
----------------------------------------------------------------
with using docker file and docker compose you can build and deploy your website on server
you can picture my project as a example:

1. After cloning, you can replace your web site with mySite files.
2. Run below command to build docker image, in my docker file i use cronjob to renew letsencrypt ssl certificate automatically every 3 months.(if you don't have ssl it will make no problem).
    - docker build -t <your_image-name> .
4. Run this command to deploy your container.
    - docker-compose up -d
5. Check your domain that is point to your server.
