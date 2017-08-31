source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'pg', '~> 0.18'
gem 'rails', '~> 5.1.3'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Turbolinks makes navigating your web application faster. Read more:
# https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'haml-rails'
gem 'bootstrap-sass'
gem "font-awesome-rails"
# List of countries and their respective states and cities
gem 'city-state'
# Authentication
gem 'devise'
# Generate fake user names, e-mails, adresses, IPs, lorem text, etc. Include
# in all environments as we might use it to seed the DB in test deploys.
gem 'devise-bootstrap-views'
gem 'devise_invitable', '~> 1.7.0'
gem 'faker'
# Use slugs instead of IDs in URLs. Makes prettier URLs, improves SEO and avoids
# leaking DB IDs (for security reasons).
gem 'friendly_id'
# jQuery is no longer installed by default on Rails 5.1
gem 'jquery-rails'
# Pagination
gem 'kaminari'
# Authorization
gem 'pundit'
gem 'formtastic', '~> 3.0'
gem 'formtastic-bootstrap'
# Contact form
gem 'mail_form'
# HTTP caching
gem 'rack-cache'
# Searching, filtering and sorting
gem 'ransack'
# Advanced select boxes https://select2.github.io/
gem 'select2-rails'
# Get e-mail notifications when exceptions happen in the production environment
gem 'exception_notification'

group :test do
  gem 'database_cleaner'
end

group :development, :test do
  # Detects N+1 queries and unused eager loading
  gem 'bullet'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger
  # console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'capybara-email'
  gem 'capybara-screenshot'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'spring-commands-rspec'
  gem 'shoulda-matchers', '~> 3.1', require: false
  gem 'selenium-webdriver'
  # code coverage analysis tool
  gem 'simplecov', require: false
end

group :development do
  gem 'awesome_print'
  gem 'better_errors'
  # Necessary to use Better Errors' advanced features (REPL, local/instance
  # variable inspection, pretty stack frame names).
  gem 'binding_of_caller'
  # A static analysis security vulnerability scanner for Ruby on Rails apps
  gem 'brakeman', require: false
  # Required by rack-mini-profiler' for call-stack profiling flamegraphs
  gem 'flamegraph'
  # Open "sent" e-mails in your browser instead of actually sending them
  gem 'letter_opener'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Database, call-stack and memory profiling
  gem 'rack-mini-profiler'
  # Required by rack-mini-profiler for memory profiling
  gem 'memory_profiler'
  gem 'rubocop'
  # Required by rack-mini-profiler for call-stack profiling
  gem 'stackprof'     # For Ruby MRI 2.1+
  # Access an IRB console on exception pages or by using <%= console %> anywhere
  # in the code.
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
