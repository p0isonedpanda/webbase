# web base
docker image for a quick start with a web server running apache 2, php, and mariadb

## details
* debian
* apache 2
* php7 (coming soon)
* mariadb (coming soon)

## usage
run `build.sh` to build the container, `launch.sh` to run it, `access.sh` to get an interactive shell, and `stop.sh` to stop the container. note that since the container is run with the `--rm` flag it will not leave a trace behind and you will not be able to commit changes after stopping the container.
