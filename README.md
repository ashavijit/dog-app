# To Use This File:

1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
2. Install [Bundler](http://bundler.io/)
3. Install [Rails](http://installrails.com/)

# To Run This App:

1. Clone this repo
2. Run `bundle install`
3. Run `rake db:create`
4. Run `rake db:migrate`
5. Run `rails s`
6. Visit `localhost:3000` in your browser

# To Run The Tests:

1. Run `rake db:test:prepare`
2. Run `rspec`

# To Deploy To Heroku:

1. Create a Heroku account
2. Install the [Heroku Toolbelt](https://toolbelt.heroku.com/)
3. Run `heroku create`
4. Run `git push heroku master`
5. Run `heroku run rake db:migrate`
6. Run `heroku open`


# To Deploy To AWS:

1. Create an AWS account
2. Install the [AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
3. Run `aws configure`
4. Run `eb init`
5. Run `eb create`
6. Run `eb open`


# To Deploy To Digital Ocean:

1. Create a Digital Ocean account
2. Install the [Digital Ocean CLI](     )
3. Run `doctl auth init`
4. Run `doctl apps create`
5. Run `doctl apps code-deploy`
6. Run `doctl apps open`

# To Deploy To Google Cloud:

1. Create a Google Cloud account
2. Install the [Google Cloud SDK](https://cloud.google.com/sdk/)
3. Run `gcloud init`
4. Run `gcloud app create`
5. Run `gcloud app deploy`
6. Run `gcloud app browse`

# To Deploy To Azure:

1. Create an Azure account
2. Install the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Run `az login`
4. Run `az webapp up`
5. Run `az webapp browse`

# To Deploy To Render:

1. Create a Render account
2. Install the [Render CLI](https://render.com/docs/deploy-cli)
3. Run `render init`
4. Run `render deploy`
5. Run `render open`

# Follow Me:

[![Twitter Follow](https://img.shields.io/twitter/follow/andrewmcodes.svg?style=social&label=Follow)](https://twitter.com/AvijitSen123)
![GitHub followers](https://img.shields.io/github/followers/ashavijit.svg?style=social&label=Follow)



# Folder Information(Ruby on Rails)

app- This directory groups using different subdirectories for the UI/layout (views and helpers), the controller (controllers files) and the models (business/application logic).

app/controllers – This directory stores controller files used by Rails to handle requests from the client.

app/assets – It contains static files, which is a need for the application’s front-end grouped into folders based on their type – JavaScript files, images, and stylesheets.

app/helpers – This subdirectory contains helper functions that make your application model, view, and controller logic focused, small and uncluttered.

app/models – This contains files that model your application’s database. The model classes make working with the database very easy.

app/views – This hold template/layout files the user of your application interacts with. The templates are a combination of HTML and data from the database.

bin – It contains Rails scripts that starts your application. It can also include other scripts that you use to set up and upgrade the application.

Config – This holds configuration files – database.yml, environment.rb, routes.rb, etc. that your application needs to run.

DB – This directory contains files/scripts that are used to manage your application database.

lib – This directory contains an extended module for your application.

log – This contains log files – server.log, development.log, test.log, and production.log, etc., that are used for debugging or monitoring your application.

public – This directory contains static files and compiled assets, such as HTML files, Javascript files, images, and stylesheets.

test – This directory holds test files you write to test your application functionality.

tmp – This directory contains temporary files like cache and pid files.

vendor – This directory contains third-party libraries.

Gemfile – This file specifies what your basic gem requirements are to run your web application. You can group the gems into development, test or production and Rails will know when to include each gem.

Gemfile.lock – Unlike the Gemfile that explicitly lists the gems you want in your application, Gemfile.lock additionally contains other gems that those you list in the Gemfile depends on that are then automatically installed to satisfy the dependencies.

Readme.md – You use this file to share essential detail about your application, such as what the app does, how to go about installing and run the application.

Rakefile – This file contains various rake tasks definitions, which helps in automating everyday administration tasks of your application.

config.ru – This is a Rack configuration file that provides an interface to the webserver to start your application.



