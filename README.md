# docker-liblwgeom

`liblwgeom` built from `postgis` source.

## Dockerfiles

### `Dockerfile.2.5.5-buster`

- Based on `debian:buster-slim` with deps:
  - [`gcc` 8.3.0-1](https://packages.debian.org/buster/gcc)
  - [`libgeos` 3.7.1](https://packages.debian.org/buster/libgeos-3.7.1)
  - [`libproj` 5.2.0-1](https://packages.debian.org/buster/libproj13)
  - [`libxml2` 2.9.4](https://packages.debian.org/buster/libxml2)
  - [`postgresql-server-dev-11` 11.14-0](https://packages.debian.org/buster/postgresql-server-dev-11)
- Output libraries in `/usr/local/lib`:
  - `liblwgeom.a`
  - `liblwgeom.la`
  - `liblwgeom-2.5.so.0.0.0`
- Output headers in `/usr/local/include`:
  - `liblwgeom.h`
  - `liblwgeom_topo.h`
