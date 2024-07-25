# WordPress + FrankenPHP Docker Image
### Tạo Docker

```
git clone https://github.com/bibicadotnet/frankenwp-php7.4
cd frankenwp-php7.4
docker build --tag bibica/frankenwp-php7.4 .
```
### Upload lên hub.docker.com
```
docker login
```
Điền user và pass
```
docker image push bibica/frankenwp-php7.4
```
