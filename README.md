### Export
```sh
yarn export
docker run --name nginx -d -p 8080:80 -v $PWD/out:/usr/share/nginx/html:ro nginx
```