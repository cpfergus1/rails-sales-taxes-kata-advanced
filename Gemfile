# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

gem 'rails', '~> 6.1.4'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'rubocop-rails', '>=2.0', require: false
gem 'bootsnap', '>= 1.4.4', require: false
gem 'devise', '~> 4.5'
gem 'figaro'
gem 'bootstrap-sass'

group :development, :test do
  gem 'sqlite3', '~> 1.4'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails', '~> 5.0.0'
end

group :test do
  gem 'factory_bot_rails'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'capybara'
  gem 'webmock'
  gem 'vcr'
  gem 'database_cleaner-active_record'
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :production do
  gem 'pg'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
