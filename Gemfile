source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
gem 'activerecord-postgres_enum', '~> 1.6'
# Use Puma as the app server
gem 'puma', '~> 5.2'
gem 'sass-rails', '~> 6.0'
gem 'uglifier',   '>= 1.3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.11'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'devise', '~> 4.8'

gem 'jquery-rails'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'newrelic_rpm'
gem 'webpacker', '~> 5.x'

# Pagination helper
gem 'pagy', '~> 3.13'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 5.0'
  gem "factory_bot_rails"
  gem 'rubocop-rails'
  gem 'faker'
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'pry'
  gem 'rails-controller-testing'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.6'

  gem 'annotate',                      require: false
  gem 'capistrano',         '~> 3.16', require: false
  gem 'capistrano-bundler', '~> 2.0',  require: false
  gem 'capistrano-rvm',     '~> 0.1',  require: false
  gem 'capistrano-rails',   '~> 1.6',  require: false
  gem 'capistrano3-puma',   '~> 5.0',  require: false
end

# Report builder
gem 'reports_kit' # Replaced by blazer reporting - 1/24/21
gem 'blazer'

# Excel and CSV support
gem 'creek'
gem 'iostreams'

# background processing
gem 'daemons'
gem 'delayed_job_active_record'
gem 'capistrano3-delayed-job', '~> 1.0'

# Auditing
gem 'paper_trail'
