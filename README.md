### Construir Imágen Docker

```bash
docker build -t gatewayservice .
```

En caso el contenedor este iniciado, se tiene que detener y eliminar

```bash
docker stop gatewayservice
docker rm gatewayservice
```