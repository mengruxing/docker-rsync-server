Rsync server
============

Reference:
----------

- [bfosberry/rsync](https://github.com/bfosberry/rsync)
- [nabeken/docker-volume-container-rsync](https://github.com/nabeken/docker-volume-container-rsync)


Start:
-----

    docker run  -d -v $PWD/data:/data -p 10873:873 ninehills/docker-rsync-server
    rsync -avP /a/v/p rsync://<docker_host>:10873/data

