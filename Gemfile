source 'https://rubygems.org'

ruby "2.1.1" # make sure .ruby-version agrees

gem 'rails', '4.0.0'

gem 'pg'
gem 'jquery-rails', '>= 3.1.0'
gem 'thin'
gem 'bootstrap-sass', "~> 2.0"
gem 'sass', "~> 3.2.0"
gem 'chosen-rails', '>= 1.1.0'
gem 'omniauth'
gem 'omniauth-github'
gem 'github_api', '>= 0.11.3'
gem 'dynamic_form'
gem 'rack-canonical-host', '>= 0.0.9'
gem 'paul_revere', '>= 1.2'
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
  gem 'launchy', '>= 2.4.2'
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails', '>= 4.4.1'
  gem 'webmock', '>= 1.17.4'
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
  gem 'sass-rails', '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
end
