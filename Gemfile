source 'http://rubygems.org'
#bundle update "rack-ssl"

gem "rails", ">= 3.2.17"

gem "rack-ssl", ">= 1.4.0"


# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'  # use SQLite only in development and testing
  gem 'ruby-debug19', :require => 'ruby-debug'
end
group :production do
  gem 'pg'  # use PostgreSQL in production (Heroku)
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'              
#  gem 'sass-rails', "~> 3.1.0"
#  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem "jquery-rails", ">= 3.1.3"


# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem "haml", ">= 5.0.0"

gem "actionmailer", ">= 3.2.15"
gem "i18n", ">= 0.6.6"

gem "sprockets", ">= 2.12.5"
gem "mail", ">= 2.5.5"
gem "rack", ">= 1.6.12"
gem "rdoc", ">= 3.12.1"
gem "json", ">= 1.6.8"
gem "activerecord", ">= 3.2.22.1"
gem "activesupport", ">= 4.1.11"
gem "actionpack", ">= 3.2.22.2"

