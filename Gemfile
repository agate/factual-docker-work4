source 'https://rubygems.org'
# source 'http://ruby.taobao.org' # chinese gem mirror

gem 'rails', '~> 4.0.12'

# basic javascript/css libs
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 3.2.0'
gem 'bootstrap_form'
gem 'font-awesome-sass', '~> 4.2.0'
gem 'bower-rails'

# server
gem 'thin'

# database
gem 'pg'
gem 'pg_search'
gem 'redis'
gem 'hiredis'
gem 'git'
gem 'octokit', "~> 3.0"

# auth
gem 'devise'
gem 'devise_invitable'
gem 'cancan'
gem 'rolify'

# lang
gem 'sass-rails'
gem 'less-rails'
gem 'haml-rails'
gem 'coffee-rails'
gem 'therubyracer' # JS libs require this (like less)

# json
gem 'oj'
gem 'yajl-ruby', require: 'yajl'
gem 'json'
gem 'multi_json'

# feature
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'bcrypt-ruby', '~> 3.0.0' # Use ActiveModel has_secure_password
gem 'jbuilder', '~> 1.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'foreigner' # Adds foreign key helpers to migrations and correctly dumps foreign keys to schema.rb
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'paperclip'
gem 'kaminari'


gem 'will_paginate'
gem 'wkhtmltopdf-binary' # for wicked_pdf
gem 'wicked_pdf'
gem 'gollum_rails', '1.5.13' # Integrated wiki
# markdown support for wiki
# don't change the version!!!
# gollum_rails require this version otherwise the preview will be break
gem 'redcarpet', '3.0.0'
gem 'aws-sdk'
gem 'browser'
gem 'curb'

gem 'whenever', :require => false # cron jobs
gem 'pry-rails' # better irb for rails console

gem 'craftsman', '~> 0.0.3'

gem 'figaro'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', :require => false
end

group :development do
  gem 'capistrano', '~> 2.15.5'
  gem 'byebug'
  gem 'mailcatcher'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'quiet_assets'
end

group :test do
  gem 'rspec-rails', '~> 2.14.1'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'selenium-webdriver', '~> 2.42.0'
end
