# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'jwt_sessions', '~> 2'
gem 'puma', '~> 3.11'
gem 'rack-cors'
gem 'rails', '~> 5.2.0'
gem 'redis', '~> 4.0'
gem 'sqlite3'

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
