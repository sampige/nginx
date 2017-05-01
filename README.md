Nginx Image
============

#### Building an image
```
$ docker build -t sampige-nginx .
```

#### Running the container
```
$ docker run --name s-nginx -p 8080:80 -d sampige-nginx
```

### Stopping the container
```
$ docker stop s-nginx
```
