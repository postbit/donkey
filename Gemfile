source 'https://rubygems.org'

gem 'rails', '4.2.5'
gem 'rails-api'
gem 'responders'

# Database
gem 'pg'

# App Server
gem 'puma'

# System
gem 'foreman', require: false
gem 'dotenv-rails'
gem 'lograge'

group :development, :test do
  gem 'rspec', '~> 3.4'
  gem 'rspec-rails', '~> 3.4'
  gem 'factory_girl_rails'
  gem 'faker'
end

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets'
  gem 'meta_request'
end

group :test do
  gem 'database_cleaner'
  gem 'webmock'
  gem 'vcr'
  gem 'timecop'
  gem 'test_after_commit'
end
