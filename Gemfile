source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'heroku'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

#gem 'mongoid'
#gem 'bson_ext'
#gem 'mongrel', '>= 1.2.0.pre2'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'heroku'
gem 'jammit'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :development, :test do
  gem 'mysql'
end
group :production do
  gem 'pg'
end