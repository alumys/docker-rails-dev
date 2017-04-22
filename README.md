# README

## Commands
```sh
# Build
$ docker-compose build

# Create database
$ docker-compose run application rake db:create

# Migration
$ docker-compose run application rake db:migrate

# Console
$ docker-compose run application rails c

# Launch
$ docker-compose up
or
$ docker-compose run --service-port application
* ...
