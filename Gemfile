source 'http://rubygems.org'

gem 'rails', '3.1.0'

gem 'handlebars_assets'
gem 'execjs', :git => 'git://github.com/sstephenson/execjs.git'
gem 'bson_ext'
gem 'mongoid', :git => 'git://github.com/mongoid/mongoid.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

group :test do
  # Pretty printed test output
  gem 'database_cleaner'
  gem 'shoulda-matchers'
end

group :development, :test do
  gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'capybara'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'mongoid-rspec'
  gem 'rspec-rails'
  gem 'fabrication'
  gem 'factory_girl_rails'
end
