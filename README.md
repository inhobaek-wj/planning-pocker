## Planning Pocker

### How to Run

``` shell
docker run -it -d \
    -p 80:80 \
    -v /$PWD/resources://usr/share/nginx/html:ro \ 
    --restart=always \
    nginx:alpine
```

