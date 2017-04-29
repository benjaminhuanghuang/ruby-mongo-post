## Install Ruby and Rails
    $ brew install ruby
    $ sudo gem install rails


## create project
    $ rails new myapp --skip-active-record

## Install Mongoid
    https://docs.mongodb.com/ruby-driver/master/mongoid/
    $ gem install mongoid

    or modify Gemfile
    gem 'mongoid', git:'https://github.com/mongodb/mongoid.git'
    $ bundle install

## Create mongoid config file
    $ rails g mongoid:config
    create config/mongoid.yml

## Run app
    $ rails s
