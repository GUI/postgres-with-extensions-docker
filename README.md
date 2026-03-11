# postgres-with-extensions-docker

Automated and up-to-date Docker images for all supported versions of PostgreSQL and all extensions available from the official [PGDG repo](https://www.postgresql.org/about/news/pgdg-apt-repository-for-debianubuntu-1432/).

Images are based upon the [official Postgres images](https://hub.docker.com/_/postgres) but with all extensiosn from PGDG pre-installed. New versions of PostgreSQL should automatically be detected and trigger new docker images to built, tagged, and pushed by a daily [GitHub Actions workflow](https://github.com/GUI/postgres-with-extensions-docker/blob/main/.github/workflows/main.yml).

## Container Registries

Images are available from either Docker Hub or GitHub Container Registery:

- [docker.io/nickblah/postgres-with-extensions](https://hub.docker.com/r/nickblah/postgres-with-extensions)
- [ghcr.io/gui/postgres-with-extensions](https://github.com/users/GUI/packages/container/package/postgres-with-extensions)

## Supported Tags and Respective Dockerfile Links

- PostgreSQL 18
    - [`18.3`, `18`, `18.3-trixie`, `18-trixie`, `trixie`, `latest`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/18/trixie/postgres/Dockerfile)
- PostgreSQL bookworm
    - [`18.3-bookworm`, `18-bookworm`, `bookworm`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/18/bookworm/postgres/Dockerfile)
- PostgreSQL 17
    - [`17.9`, `17`, `17.9-trixie`, `17-trixie`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/17/trixie/postgres/Dockerfile)
- PostgreSQL 17-bookworm
    - [`17.9-bookworm`, `17-bookworm`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/17/bookworm/postgres/Dockerfile)
- PostgreSQL 16
    - [`16.13`, `16`, `16.13-trixie`, `16-trixie`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/16/trixie/postgres/Dockerfile)
- PostgreSQL 16-bookworm
    - [`16.13-bookworm`, `16-bookworm`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/16/bookworm/postgres/Dockerfile)
- PostgreSQL 15
    - [`15.17`, `15`, `15.17-trixie`, `15-trixie`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/15/trixie/postgres/Dockerfile)
- PostgreSQL 15-bookworm
    - [`15.17-bookworm`, `15-bookworm`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/15/bookworm/postgres/Dockerfile)
- PostgreSQL 14
    - [`14.22`, `14`, `14.22-trixie`, `14-trixie`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/14/trixie/postgres/Dockerfile)
- PostgreSQL 14-bookworm
    - [`14.22-bookworm`, `14-bookworm`](https://github.com/GUI/postgres-with-extensions-docker/blob/main/14/bookworm/postgres/Dockerfile)
