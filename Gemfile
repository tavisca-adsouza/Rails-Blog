source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0', '>= 6.0.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4', '>= 1.4.2'
# Use Puma as the app server
gem 'puma', '~> 4.3', '>= 4.3.1'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 6.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.9', '>= 2.9.1'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Make errors prettier
gem 'better_errors', '~> 2.8'
# Bulma CSS
gem 'bulma-rails', '~> 0.8.0'
# Simple forms
gem 'simple_form', '~> 5.0', '>= 5.0.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 11.0', '>= 11.0.1'
  #gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.30'
  gem 'selenium-webdriver', '~> 3.142', '>= 3.142.7'

end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '~> 4.0', '>= 4.0.1'
  gem 'listen', '~> 3.2', '>= 3.2.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
  # Guard is a command line tool to easily handle events on file system modifications.
  gem 'guard', '~> 2.16', '>= 2.16.1'
  # reload the browser after changes to assets/helpers/tests
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false
  #gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2019', '>= 1.2019.3'
#gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]