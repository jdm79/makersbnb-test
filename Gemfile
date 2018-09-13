# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

gem 'bcrypt'
gem 'sinatra'
gem 'rspec'
gem 'capybara'
gem 'activerecord'
gem 'simplecov'
gem 'simplecov-console'
gem 'sinatra-activerecord'
gem 'rake'

group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'sqlite3'

  gem "puma"
end
