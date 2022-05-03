# Hosting multiple sites with traefik

## Javier Lopez tutorials
* http: [Host several sites in a single box with docker and traefik v2, http](http://javier.io/blog/en/2020/12/01/host-several-sites-in-a-single-box-with-docker-and-traefik-http.html)
* https: [Host several sites in a single box with docker and traefik v2, https](http://javier.io/blog/en/2020/12/01/host-several-sites-in-a-single-box-with-docker-and-traefik-https.html)

## commands
```
cd traefik
docker-compose up -d
cd ../site1
docker-compose up -d
cd ../site2
docker-compose up -d
```



## Information

/!\ don't forget to edit hosts file in dev mode
```
127.0.0.1 site1.com
127.0.0.1 site2.com
```

## Websites access

the websites are accessible at the addresses
```
http://site1.com
http://site2.com
```