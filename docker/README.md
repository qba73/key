# Keycloak in development mode

## Start Keycloak Container

```shell
docker run --name mykeycloak -p 8080:8080 \
        -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin \
        quay.io/keycloak/keycloak:latest \
        start-dev
```

## Initial Setup

Setup Keycloak and follow the [getting started guide](https://www.keycloak.org/getting-started/getting-started-docker).
