# WordPress with Varnish on Docker
## Requirement:
  * Docker 17.06.0+
  * Docker Compose 1.14.0+

## How to start:
### Pull repo from git
```
git pull https://github.com/m1g0r/varnish-wordpress-demo-docker.git
```
### Run WordPress with Varnish
```
cd varnish-wordpress-demo-docker
```
```
docker-compose up -d
```
Open WordPress
[http://127.0.0.1](http://127.0.0.1)

### Delete WordPress with Varnish
```
docker-compose down
```

### Delete WordPress, Varnish with data
```
docker-compose down --volume
```