# WordPress + FrankenPHP Docker Image
### Tạo Docker

```
git clone https://github.com/bibicadotnet/frankenwp-php8.3
cd frankenwp-php8.3
docker build --tag bibica/frankenwp-php8.3 .
```
### Upload lên hub.docker.com
```
docker login
```
Điền user và pass
```
docker image push bibica/frankenwp-php8.3
```
