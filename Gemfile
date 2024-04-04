source 'https://rubygems.org'

ruby "2.1.1" # make sure .ruby-version agrees

gem 'rails', '7.0.8.1'

gem 'pg'
gem 'jquery-rails', '>= 4.0.1'
gem 'thin', '>= 1.7.0'
gem 'bootstrap-sass', "~> 2.0"
gem 'sass', "~> 3.2.0"
gem 'chosen-rails', '>= 1.1.1'
gem 'omniauth', '>= 1.3.1'
gem 'omniauth-github', '>= 1.1.2'
gem 'github_api', '>= 0.13.1'
gem 'dynamic_form'
gem 'rack-canonical-host', '>= 0.2.1'
gem 'paul_revere', '>= 1.3'
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
  gem 'capybara', '>= 2.3.0'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails', '>= 4.5.0'
  gem 'webmock'
  gem 'poltergeist', '>= 1.5.1'
  gem 'database_cleaner'
end

group :test, :development do
  gem 'rspec-rails', '~> 2.99', '>= 2.99.0'
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
