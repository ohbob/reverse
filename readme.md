# install docker
# install docker-compose

```
git clone https://github.com/ohbob/reverse.git
``` 
```
cd reverse/backend
docker-compose up -d
cd ../proxy
docker-compose up -d
```

Replace 1.1.1.1 with an actuall server ip.

Open up your browser and go to http://1.1.1.1:81/
login with the default admin user:
```angular2html
Email:    admin@example.com
Password: changeme
```
change the password and setup the backend proxy as in example bellow

ps: point your A record for the domain to the ip address of the reverse proxy and fill out the rest of the fields

![proxy setup image](/proxy/proxy-setup.png)
