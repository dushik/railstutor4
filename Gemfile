source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.6'
gem 'bootstrap-sass', '2.3.2.0'
gem 'haml-rails'
gem 'bcrypt-ruby','3.1.5'

# Use sqlite3 as the database for Active Record
group :production do
  gem 'pg', '0.17.1'
  gem 'rails_12factor', '0.0.2'
end

group :development do
  gem 'sqlite3'
  gem 'annotate', '~>2.6.5'
  gem 'better_errors'
  gem 'guard-migrate'
  gem 'guard-spring'
  gem 'guard-rails'
  gem 'binding_of_caller'
  # gem 'guard-haml'
end

group :development, :test do
  gem 'spring-commands-rspec'
  gem 'rspec-rails'
  gem 'rspec-its'
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'spork-rails', github: 'sporkrb/spork-rails' # rubygems version not rails 4 compatible
  gem 'guard-spork'
  gem 'childprocess'
  gem 'guard-bundler'
  # Integrates jasmine js testing
  gem 'jasmine-rails'
  # With guard
  gem 'guard-jasmine', git: "git://github.com/guard/guard-jasmine.git", branch: "jasmine-2"
  # Checks ruby code grammar
  gem 'rubocop', require: false
  # With rspec
  gem 'rubocop-rspec'
  # With guard
  gem 'guard-rubocop'
end

group :test do
  gem 'selenium-webdriver', '2.43.0'
  gem 'capybara', '2.4.3'
  gem 'factory_girl_rails'
  gem 'cucumber'
  # , '1.2.5' # Spork not supported as of Cucumber 1.3.0, need to use 1.2.5
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

