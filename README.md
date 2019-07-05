# README

This README would normally document whatever steps are necessary to get the rails docker application up and running.

Things you may want to cover:

* Ruby version is 2.6.2
* Rails version is 5.0.1
* Database creation
  > docker­-compose run --­­user "$(id ­-u):$(id -­g)" drkiq rake db:reset

  > docker-compose run --user "$(id -u):$(id -g)" drkiq rake db:migrate

* Run services
  > docker-compose up

* Start the server in development environment
  > http://localhost:8000/
