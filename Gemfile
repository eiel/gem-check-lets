source 'https://rubygems.org'

gem 'rails', '3.2.18'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'

gem 'json'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'libv8', '3.11.8.17'
  gem "therubyracer"

  gem 'uglifier', '>= 1.0.3'

  gem 'less', "~> 2.3.0"
  gem 'turbo-sprockets-rails3'
end

gem 'turbolinks'
gem 'jquery-rails', '2.0.1'
gem 'jquery-turbolinks'
gem 'jquery-ui-rails'
gem 'client_side_validations'
gem 'client_side_validations-turbolinks'
gem 'eyecon-colorpicker-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'rvm-capistrano'
gem 'capistrano-unicorn', :require => false
gem "capistrano_database_yml", :require => false

group :test, :development do
  gem "rspec-rails", "~> 2.12"
  gem "capybara"
  gem "poltergeist"
  gem "spork-rails"
  gem 'rspec-html-matchers'
  gem "parallel_tests"
  gem 'delorean'
  gem 'simplecov'
  gem 'ci_reporter'
  gem 'simplecov-rcov'
  gem 'pry-byebug'
end

# guard
group :development do
  gem 'guard'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-rails'
  gem 'ruby_gntp'
end

group :darwin do
  gem 'rb-fsevent'
end

group :linux do
  gem 'rb-inotify'
end

group :test do
  gem "cucumber-rails", require: false
  gem "database_cleaner"
  gem "codeclimate-test-reporter", require: nil
end

group :development do
  gem "rails-erd"
  gem "thin"
  gem 'rack-mini-profiler'
  gem 'yard-rails', require: false
  gem 'yard-cucumber', require: false
  gem 'rails_best_practices', require: false
  gem 'markdown', require: false
  gem "better_errors"
  gem "binding_of_caller"
  gem "view_source_map"
  gem "letter_opener"
end

gem 'devise'
gem 'devise-encryptable'
gem 'cancan'
gem 'kaminari'
gem 'factory_girl', '< 4.3'
gem 'factory_girl_rails'

gem "squeel", '> 1.1'

gem 'rack-cache', :require => 'rack/cache'
gem 'dragonfly', '~>0.9.11'

gem 'exifr'

gem 'haml-rails'

gem 'twitter-bootstrap-rails', '=2.2.6'
gem "less-rails", '~> 2.3.0'

gem 'jquery_mobile_rails'
gem 'jpmobile'

gem 'exception_notification'

gem 'httpclient'

# console support
gem 'awesome_print'
gem 'pry-rails'

gem 'foreigner'
gem 'ransack'
gem "rails_autolink", "~> 1.1.0"
