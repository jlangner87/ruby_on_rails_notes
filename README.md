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

- It is a separation of the presentation layer and the backend layer

1. Presentation Layer (what the user sees when interacting with the application)
2. Backend Layer (All of the logic code for operating the application)

### Model Overview

1. Resources within the application
   - examples: posts, comments, users, listings, etc...
2. Will generally access a database
   - Sqlite is the default database with Rails

### View Overview

1. Makes up the front-end or presentation layer of the application
2. Shares data with controllers
   - The app/views directory has a subdirectory for each controller
3. Operates in standard web templates (HTML, CSS, JavaScript)
   - Ruby is embedded into the HTML file as an extension "action_name.html.erb"
   - Embedded Ruby is done with the HTML tag <%= ... %>

### Controller Overview

1. The backend brains/logic of the application
   - examples: users_controller, listings_controller, pages_controller
2. Determines how user requests are handled and returned to the user via views

![](mcv-infograph.png)

## Rails App Structure

### App

#### assets _(stores static assets)_

##### config

- .keep

##### images

##### stylesheets _(stores css/scss stylesheets)_

- application.css _(manifest file that is available to all application views)_

#### channels _(makes realtime communication available to the application)_

- channel.rb
- connection.rb

#### controllers _(where all additional controllers will be stored)_

##### concerns

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

##### concerns

- .keep
- application_record.rb

#### views _(all views are served from this directory)_

##### layouts

- application.html.erb

- mailer.html.erb
- mailer.text.erb

### Bin

- bundle
- importmap
- rails
- rake
- setup

### Config

#### environments

- development.rb
- production.rb
- test.rb

#### initializers

- assets.rb
- content_security_policy.rb
- filter_parameter_logging.rb
- inflections.rb
- permissions_policy.rb

#### locales

- en.yml

- application.rb
- boot.rb
- cable.yml
- environment.rb
- importmap.rb
- mastery.key
- puma.rb
- routes.rb
- storage.yml

### DB

#### development.sqlite3

#### seeds.rb

### Lib

#### assets

- .keep

#### tasks

- .keep

### Log

#### .keep

#### .development.log

### Public

#### 404.html

#### 422.html

#### 500.html

### Storage

### Test

### Tmp

### Vendor

## Generate a Model

## Generate a Controller

## Declaring Routes
