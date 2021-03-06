source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Blacklight Gems
gem 'blacklight', '~> 6.0'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
gem 'therubyracer'

# CAS Authentication
# April 25, 2016: Need to use GitHub instead of Gem
# See https://github.com/rubycas/rubycas-client-rails/issues/27
gem 'rubycas-client', git: 'https://github.com/rubycas/rubycas-client.git', branch: 'master'

# dotenv - For storing production configuration parameters
gem 'dotenv-rails', '~> 2.1.1'

# clipboard - Uses clipboard.js to provide "Copy to Clipboard" functionality
gem 'clipboard-rails', '~>1.7.1'

# Pagination
gem 'will_paginate', '~> 3.1.0'
gem 'will_paginate-bootstrap', '~> 1.0.0'

# Table sorting
gem 'ransack', '~> 1.8.3'

# Used by Rake tasks to generate sample data
gem 'faker', '~> 1.8'

gem 'http', '~> 2.2.2'

# RFC-complient URI and URI template handling
gem 'addressable', '~> 2.5'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'solr_wrapper', '>= 0.3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem 'minitest-reporters', '~> 1.1.8'
  gem 'minitest-ci', '~> 3.0.3'

  # Code analysis tools
  gem 'rubocop', '~> 0.39.0', require: false
  gem 'rubocop-checkstyle_formatter', '~> 0.2.0', require: false

  gem 'simplecov', require: false
  gem 'simplecov-rcov', require: false
end

gem 'rsolr', '~> 1.0'
