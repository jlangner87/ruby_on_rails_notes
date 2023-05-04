# Intro to Ruby on Rails

## Resources

1. Official Ruby on Rails Documentation [Ruby on Rails](rubyonrails.org)
2. Ruby on Rails Packages [Ruby Gems](rubygems.org)

## Getting Started

1. Create a new rails application
   `rails new application_name`
2. Run Rails server
   `rails s`
3. Default root route

- localhost:3000

## MVC Overview

### Model

### View

### Controller

![](mcv-infograph.png)

## Rails App Structure

### App Directory

#### assets _(stores static assets)_

- config
  - .keep
- images
- stylesheets _(stores css/scss stylesheets)_
  - application.css _(manifest file that is available to all application views)_

#### channels _(makes realtime communication available to the application)_

- channel.rb
- connection.rb

#### controllers _(where all additional controllers will be stored)_

- concerns
  - .keep
- application*controller.rb *(default functionality)\_

#### helpers _(helper methods used in views templates)_

- application_helper.rb

#### javascript _(makes JavaScript available to the application)_

- controllers
  - application.js
  - index.js
- application.js

#### jobs

- application_jobs.rb

#### mailers

- application_mailers.rb

#### models _(where models are stored)_

- concerns
  - .keep
- application_record.rb

#### views

- layouts _(all views are served from this directory)_
  - application.html.erb
- mailer.html.erb
- mailer.text.erb

### Bin Directory

## Generate a Model

## Generate a Controller

## Declaring Routes
