# php-jit-playground

## How To Use

```shell
docker compose build

docker compose up -d

docker compose exec php /bin/sh

cd /workspace

php -d opcache.jit_debug=1 -d opcache.opt_debug_level=0x10000  sample.php 
```