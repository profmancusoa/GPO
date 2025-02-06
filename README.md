# GPO

Repository per il corso di GPO

# Come usare projectlibre

Per eseguire projectlibre usa il seguente comando

```bash
docker run --rm -ti -v /tmp/.X11-unix:/tmp/.X11-unix -v /dev/shm:/dev/shm -v <TUO PATH LOCALE>:/root/gpo --device /dev/dri -e DISPLAY=$DISPLAY profmancusoa/projectlibre /root/projectlibre-1.9.3/projectlibre.sh
```
