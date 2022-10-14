# sonarqube-ssl

How deploy sonarqube with self-firmed certificated

## Ejecutamos en la terminal

```bash

docker-compose up -d

```

### Verificamos que estén corriendo los dos contenedores

```bash
docker container ls
```

### Inicio de session

Una vez ejecutado podemos ir a <https://localhost:443>, en el login nos pedira un user y un password el cual nos pedira cambiar los cuales son `admin` y el password es `admin`.

Una vez que hayas iniciado session te pedira cambiar tu password.

Ahora si disfruta tener tu sonarqube con ssl autofirmado y lo mejor de todo en `docker compose`.
