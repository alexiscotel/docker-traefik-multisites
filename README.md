# gestion et redirection de multisite avec traefik

tuto de jarvier pour http: [Host several sites in a single box with docker and traefik v2, http](http://javier.io/blog/en/2020/12/01/host-several-sites-in-a-single-box-with-docker-and-traefik-http.html)

marche à suivre :
```
cd traefik
docker-compose up -d
cd ../site1
docker-compose up -d
cd ../site2
docker-compose up -d
```