source 'https://rubygems.org'

ruby '2.2.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
gem 'pg', '~> 0.18' # Use Postgresql for the database.
gem 'puma'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'foundation-rails', '~> 5.5'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'refinerycms', git: 'https://github.com/refinery/refinerycms', branch: 'master'

gem 'quiet_assets', group: :development

# Add support for searching inside Refinery's admin interface.
gem 'refinerycms-acts-as-indexed', ['~> 2.0', '>= 2.0.0']

# Add support for Refinery's custom fork of the visual editor WYMeditor.
gem 'refinerycms-wymeditor', ['~> 1.0', '>= 1.0.6']

# The default authentication adapter
gem 'refinerycms-authentication-devise', '~> 1.0'

gem 'refinerycms-portfolio', github: 'refinery/refinerycms-portfolio', branch: 'master'

gem "jquery-slick-rails" #  the jQuery Slick plugin by Ken Wheeler - in the rails pipeline

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'guard-rspec', require: false
  gem 'launchy', require: false
  gem 'terminal-notifier-guard', require: false
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :production do
  gem 'rails_12factor', '~> 0.0.3' # required for Heroku
end