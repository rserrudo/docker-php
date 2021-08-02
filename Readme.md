# Imagen Docker PHP + Alphine + Extensiones

## Imagen de PHP

Esta imagen contiene esta basada en PHP + Alpine junto con las siguientes extensiones:
- GD
- mysqli
- pdo

## Compilar imagen Docker

Iniciar sesión en el CLI de Docker:

```
bash
docker login -u username
```

Versión 7.3.28 arm64/amd64:

```
bash
docker build -t username/php:7.3.28-fpm-alpine3.13-arm64 .
```
Versión 8.0.8 arm64/amd64:

```
bash
docker build -t username/php:8.0.8-fpm-alpine3.14-arm64 .
```
Subir a los repositorios de Docker:
```
bash
docker push username/php:tag
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
