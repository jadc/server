# server
A collection of Docker compose files I have written for use on my home server.

## Usage
Ensure you have Docker installed, then, clone this repository.

Run `docker compose up -d` in the root of the repository. This will run all the services.

The typical server files will be located in the `data` subdirectory within each service's directory. Do not commit this directory.

## File Structure
Ensure the following directory structure exists on the server.

```bash
/data
/data/media/library/movies       # *arr
/data/media/library/shows        # *arr
/data/media/downloads            # torrent
/data/media/downloads/completed  # torrent
/data/sync                       # syncthing
```
