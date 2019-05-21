# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'sinatra'
gem 'rack-bodyparser'

group :development do
  gem 'bundler', '~> 1.17'
  gem 'docker-api'
  gem 'guard-rake'
  gem 'rack-test'
  gem 'rake', '~> 10.0'
  gem 'rspec', '~> 3.0'
  gem 'rubocop'
  gem 'sinatra-contrib'
  gem 'solargraph'
  gem 'thin'
end

group :development, :test do
  gem 'dotenv'
  gem 'response_code_matchers'
end
