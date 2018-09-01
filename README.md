# Rails App Starter

This is a starter Rails project that is setup with the basics of most apps that I write.

It is personalised for me.

- Ruby 2.5.1
- Rails 5.2.1
- TailwindCSS
- Turbolinks
- PostgreSQL

## How to use

1.  Clone the repo, then `cd` into the project folder
2.  `rm -rf .git` - this clears the git config/history
3.  `git init` - start a new git history
4.  `cp config/database.yml.example config/database.yml` - update database name to suit app
5.  `bundle install` - Install Rubygems
6.  `yarn install` - Installs javascript dependencies
7.  `docker-compose up` - Starts docker services
8.  `bin/rails db:create:all` - create dev and test database
