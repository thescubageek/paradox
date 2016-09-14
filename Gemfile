source 'https://rubygems.org'

ruby "2.3.1"

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem "active_model_serializers", "~> 0.8.2"
gem "activerecord-session_store"

gem "sidekiq", "~> 4.1"
gem 'sidekiq-unique-jobs'
gem 'sidekiq-failures'
gem 'sidekiq-limit_fetch'
gem 'sinatra', :require => nil

gem "non-stupid-digest-assets"
gem "ranked-model"
gem "retriable", '~> 2.1'

gem "pg"
gem "listen"
gem "rack-cors"

gem 'puma', '~> 3.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'

gem 'phaser-rails'

group :production do
  gem "rails_12factor"
  #gem "newrelic_rpm"
  #gem "dalli"
  gem 'autoscaler'
end

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
  gem "parallel_tests"
  gem "better_errors"
  gem "binding_of_caller"
  gem "railroady"
  gem "bullet"
end

group :development, :test do
  # secrets
  gem "dotenv-rails", "~> 0.11.1"
  # debugging
  gem "pry-byebug"
  # server processes runner
  gem "foreman"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
