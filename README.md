# logrotate-docker

Rotates docker json logs

## Usage

    docker run --volume /var/lib/docker/containers:/var/lib/docker/containers:rw snaptv/logrotate
