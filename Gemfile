source 'http://rubygems.org'

gem 'rails', '3.2.22'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'devise', '~> 2.1', '>= 2.1.2'
gem 'devise-encryptable'
gem 'cancan'
gem 'nifty-generators', :group => :development
gem 'event-calendar', :require => 'event_calendar'
gem 'populator'
gem 'faker'
gem 'will_paginate'
gem 'escape_utils'
gem 'prawn'
gem 'quiet_assets'
gem 'pg', '~> 0.11'

group :assets do
  gem 'sass-rails', "  ~> 3.2.3"
  gem 'coffee-rails', "~> 3.2.1"
  gem 'uglifier', '>=1.0.3'
	gem 'twitter-bootstrap-rails'
	gem 'less-rails'
	gem 'therubyracer'
end

gem 'jquery-rails'
gem 'google-analytics-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
#gem "mocha", :group => :test

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
	gem 'sqlite3'
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  # gem 'capistrano-rbenv'
  gem 'capistrano-rvm'
  gem 'capistrano-passenger'
end

ruby "2.3.3"
