# Portfolio Builder

Backend for portfolio builder app

# Prerequisites
- Ruby 2.6.3
- Postgres v11.14

# Steps to run
- Firstly, make a copy of the `config/database.example.yml` file and name it as `database.yml`.
In this file, enter the configuration of your Postgres DB instance.
- Install the project dependencies using `bundle install`
- Next create the database by running `rake db:create` followed by running the migrations using `rake db:migrate`
- You can now run the server by running command `rails s` which will run the server on port 3000.

# Built with

- Ruby on Rails 6.0.2
