source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.6'
# Use sqlite3 as the database for Active Record
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :development do
  gem 'sqlite3'
  gem 'binding_of_caller'
  gem 'better_errors'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Add Faker Gem to help generate development data automatically
gem 'faker'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
group :doc do
  gem 'sdoc', '~> 0.4.0', require: false
end

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Adding a CSS bootstrap
gem 'bootstrap-sass', '~> 3.2.0'

# Add Devise gem as user authenication
gem 'devise'
# Add Pundit to control user authorization
gem 'pundit'
# Add Figaro gem to handle data security
gem 'figaro', '1.0'
# Add Redcarpet gem to add markdown to posts
gem 'redcarpet'
# Add carrierwave for image uploading
gem 'carrierwave'
# Add minimagick for image sizing
gem 'mini_magick'
# Add fog as cloud services library to upload to Amazon S3
gem 'fog'
# Add pagination gem
gem 'will_paginate', '~> 3.0.5'
# Add Rspec
group :development, :test do
  gem 'rspec-rails', '~> 3.1.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails', '~> 4.0'
end
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
