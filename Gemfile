source 'https://rubygems.org'

ruby "2.1.1" # make sure .ruby-version agrees

gem 'rails', '6.1.7.3'

gem 'pg'
gem 'jquery-rails', '>= 4.0.1'
gem 'thin'
gem 'bootstrap-sass', "~> 2.0"
gem 'sass', "~> 3.2.0"
gem 'chosen-rails'
gem 'omniauth'
gem 'omniauth-github'
gem 'github_api'
gem 'dynamic_form'
gem 'rack-canonical-host'
gem 'paul_revere'
gem 'kramdown'
gem 'newrelic_rpm'
gem 'rack-ssl-enforcer'

group :development do
  gem 'localtunnel'
  gem 'pry'
  gem 'pry-rails'
  # gem 'pry-debugger'
  gem 'pry-remote'
  gem 'debugger-linecache', '1.2.0'
end

group :test do
  gem 'launchy'
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails'
  gem 'webmock'
  gem 'poltergeist'
  gem 'database_cleaner'
end

group :test, :development do
  gem 'rspec-rails', '~> 2.14', '>= 2.14.2'
  gem 'simplecov', require: false
  gem 'dotenv'
  gem 'guard-livereload'
end

group :development, :darwin do
  gem 'rb-fsevent', '~> 0.9.1'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
end
