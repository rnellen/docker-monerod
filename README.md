# docker-monerod
*[monero](http://monero.org) container based on alpine-glibc*

Make sure you have a `.env` file in the root folder. Have a look at env.example to see what needs to be configured. This file is used by the docker-compose to bootstrap the services.

# Running the Daemon
    docker-compose up -d monerod

# Checking the container status
    docker-compose log
