# Running Keycloak with MySQL Database in Docker

This docker compose file will run a Keycloak and MySQL instance as a docker container. Keycloak will connect to the MySQL database using JDBC.

Blog: https://www.czetsuyatech.com/2021/07/docker-run-keycloak-with-mysql.html

**Help me keep this project updated by supporting me on Patreon.*

## Prerequisites

Docker server running on your local machine.

## Running this Project

```sh
docker-compose up
```

## What's inside the project?

 - The docker compose file
 - keycloak/import-realm.json - This realm will imported into Keycloak once a new instance is created. This file is use in the exercise available at https://github.com/czetsuya/keycloak-angular-auth/blob/master/config/keycloak-auth-realm.json.
