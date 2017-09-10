# Syncthing-Docker
A Docker container for Syncthing.

## Volumes
This container uses the following volumes:
- `/mnt` for data storage.
- `/home/syncthinguser/.config/syncthing` for configuration storage.

## Ports
This container uses the following ports:
- `8384` for the WebGUI
- `22000` for filesyncing
- `21027/udp` for discovery
