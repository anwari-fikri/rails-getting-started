### First things first
change ruby version in Gemfile to your current ruby version first.
...then create empty Gemfile.lock

### Docker
Commands are referred from https://docs.docker.com/samples/rails/

# run these commands
docker compose run --no-deps web rails new . --force --database=postgresql
docker compose up --build

# ...then in another terminal
docker compose run web rake db:create

### README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
