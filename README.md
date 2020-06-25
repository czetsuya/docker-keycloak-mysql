[![patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/bePatron?u=12280211)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

**Help me keep this project updated by supporting me on Patreon.*

# Running Keycloak with MySQL Database in Docker

This docker compose file will run a Keycloak and MySQL instance as a docker container. Keycloak will connect to the MySQL database using JDBC.

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

## Authors

 * **Edward P. Legaspi** - *Java Architect* - [czetsuya](https://github.com/czetsuya)
