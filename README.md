# docker-liblwgeom

`liblwgeom` built from `postgis` source.

## Dockerfiles

### `Dockerfile.2.5.5-buster`

- Based on `debian:buster-slim`.
- Output libraries in `/usr/local/lib`:
  - `liblwgeom.a`
  - `liblwgeom.la`
  - `liblwgeom-2.5.so.0.0.0`
- Output headers in `/usr/local/include`:
  - `liblwgeom.h`
  - `liblwgeom_topo.h`
