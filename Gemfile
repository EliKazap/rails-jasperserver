source 'https://rubygems.org'

gem 'bundler', '>= 1.8.4'
gem 'rails', '3.2.22.5'

# Declare your gem's dependencies in jasperserver-rails.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# jquery-rails is used by the dummy application
gem 'jquery-rails'

group :development, :test do
  gem 'thin'
end

group :test do
  gem 'sqlite3'
  gem 'vcr', '~> 2.9'
  gem 'webmock', '~> 1.24'
end
