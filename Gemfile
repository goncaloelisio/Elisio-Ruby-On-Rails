source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'
# A library for generating fake data such as names, addresses, and phone numbers.
gem 'faker', '~> 2.14'
# Pagination library for Rails, Sinatra, Merb, DataMapper, and more
gem 'will_paginate', '~> 3.3'
# Format will_paginate html to match Twitter Bootstrap styling
gem 'bootstrap-will_paginate', '~> 1.0'
# Official Sass port of Bootstrap 2 and 3.
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors', '~> 2.9', '>= 2.9.1'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
  # Brings back `assigns` and `assert_template` to your Rails tests
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.5'
  # minitest provides a complete suite of testing facilities supporting TDD, BDD, mocking, and benchmarking.
  gem 'minitest', '~> 5.14', '>= 5.14.2'
  # Create customizable MiniTest output formats.
  gem 'minitest-reporters', '~> 1.4', '>= 1.4.2'
  # Guard automates various tasks by running custom rules whenever file or directories are modified.
  gem 'guard', '~> 2.16', '>= 2.16.2'
  # Minitest allows to automatically & intelligently launch tests with the minitest framework when files are modified.
  gem 'guard-minitest', '~> 2.4', '>= 2.4.6'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]