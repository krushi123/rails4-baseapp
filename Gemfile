source 'https://rubygems.org'
ruby '2.1.0'

gem 'rails', '~> 4.1.0.beta1'

gem 'rb-inotify', :group => [:development, :test]   # monitor file changes without hammering the disk



# Monitoring
gem 'rack-timeout', '~> 0.1.0beta3'
gem 'newrelic_rpm'
gem 'airbrake'                # use with airbrake.io or errbit
# gem 'airbrake_user_attributes'  # use with self-hosted errbit; see config/initializers/airbrake.rb
# gem 'rack-google-analytics'

# Data
gem 'pg'
# gem 'jbuilder'

# Assets
gem 'sass-rails'
gem 'haml-rails'
gem 'simple_form'
gem 'uglifier'
gem 'headjs-rails'

# Javascript
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'nprogress-rails'

# CoffeeScript
# Not needed in production if precompiling assets
gem 'coffee-rails'
# Uncomment if node.js is not installed
gem 'therubyracer', platforms: :ruby

# Design
gem 'bootstrap-sass'

# Email
gem 'premailer-rails'

# Authentication
gem 'devise'
gem 'cancan'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-google-oauth2'
gem 'omniauth-linkedin'

# Admin
gem 'rails_admin'

# Workers
gem 'sidekiq'
gem 'devise-async'
gem 'sinatra', require: false

# Utils
gem 'addressable'
gem 'settingslogic'

group :development do
  # Docs
  gem 'sdoc', require: false    # bundle exec rake doc:rails

  # Errors
  gem 'better_errors'
  gem 'binding_of_caller'     # extra features for better_errors
  gem 'meta_request'          # for rails_panel chrome extension

  gem 'git-deploy'

  # Guard
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'rack-livereload'
end

group :development, :test do
  # Use spring or zeus
  gem 'spring'                  # keep application running in the background
  gem 'spring-commands-rspec'
  gem 'thin'
  # Debugging
  gem 'pry'                   # better than irb
  gem 'byebug'                # ruby 2.0 debugger with built-in pry
  gem 'pry-rails'               # adds rails specific commands to pry
  gem 'pry-byebug'              # add debugging commands to pry
  gem 'pry-stack_explorer'      # navigate call stack
  gem 'awesome_print'           # pretty pring debugging output

  # Testing
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'capybara-webkit'

  # Logging
  gem 'quiet_assets'
end

group :test do
  gem 'minitest'                # include minitest to prevent require 'minitest/autorun' warnings

  # Helpers
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'timecop'               # Mock Time

  # Coverage
  gem 'simplecov', require: false

  gem 'rspec-sidekiq'
end

group :production do
  gem 'dalli'                   # memcached
end

