ruby '2.5.1'

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'

# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'


gem 'sitemap_generator'
gem 'dalli'
gem 'kaminari' # must be included before elastic search for paginated results
gem 'mini_magick', '~> 4.8'
gem 'memcachier'
gem 'newrelic_rpm'
gem 'numbers_in_words'
gem 'omniauth'
gem 'route_downcaser'




# dev
swell_engines_path = ENV['SWELL_ENGINE_PATH'] || '../engines'

# Dev *****
# gem 'swell_id', path: "#{swell_engines_path}/swell_id"
# gem 'pulitzer', path: "#{swell_engines_path}/pulitzer"
# gem 'scuttlebutt', path: "#{swell_engines_path}/scuttlebutt"
# gem 'bazaar', path: "#{swell_engines_path}/bazaar"
# gem 'bunyan', path: "#{swell_engines_path}/bunyan"
# gem 'edison', path: "#{swell_engines_path}/edison"
# gem 'socratic', path: "#{swell_engines_path}/socratic"
# gem 'dewey', path: "#{swell_engines_path}/dewey"

# Prod *****
gem 'swell_id', git: 'https://github.com/gkparishphilp/swell_id.git', :tag => "v1.4.0", :branch => 'master'
gem 'pulitzer', git: 'https://github.com/gkparishphilp/pulitzer.git', :tag => "v1.20.1", :branch => 'master'
gem 'scuttlebutt', git: 'https://github.com/gkparishphilp/scuttlebutt.git', :tag => "v1.6.0", :branch => 'master'
gem 'bunyan', git: 'https://github.com/Groundswell/bunyan.git', :tag => "v2.0.0", :branch => 'master'
gem 'edison', git: 'https://github.com/Groundswell/edison.git', :tag => "v2.0.0", :branch => 'master'
gem 'socratic', git: 'https://github.com/Groundswell/socratic.git', :tag => "v2.3.3", :branch => 'master'




group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
