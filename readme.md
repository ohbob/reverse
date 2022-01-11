# install docker
# install docker-compose

```
clone git https://github.com/ohbob/reverse.git
``` 
```
cd backend
docker-compose up -d
cd ..
cd proxy
docker-compose up -d
```

Open up your browser and go to http://localhost:81/
login with the default admin user:
```angular2html
Email:    admin@example.com
Password: changeme
```
change the password and setup the backend proxy as in example bellow

![proxy setup image](/proxy/proxy-setup.png)
