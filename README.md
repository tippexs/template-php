# Devguid

All important containers are located in the `compose.yml` file.

Note: There is no need to have PHP installed locally. This projects makes full use of Docker!

## Run composer or other commands inside the container

`docker compose run app /bin/bash`
`docker compose run app composer`

Per default files are mountes to `/opt/src/`

