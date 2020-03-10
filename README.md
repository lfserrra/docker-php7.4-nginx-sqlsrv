# Docker: PHP 7.4 + Nginx + Driver Sqlsrv

First, edit root path in the .docker/nginx/nginx.conf file for the root path of your project.
Example: 
```sh
root /var/www
```
or 
```sh
root /var/www/public
```

### To recompile when changing Dockerfile (both PHP and Nginx)
```
docker-compose build 
```

### To start the docker-compose in the background (-d)
```
docker-compose up -d 
```

### To stop docker-compose
```
docker-compose stop
```

### To stop and exclude docker-compose
```
docker-compose down
```

### Access port 8000
```
http://localhost:8000/
```