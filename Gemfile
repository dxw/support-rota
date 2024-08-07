# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby "3.3.4"

gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap", ">= 4.3.1"
gem "coffee-rails", "~> 5.0"
gem "haml-rails"
gem "high_voltage"
gem "icalendar"
gem "jbuilder", "~> 2.11"
gem "jquery-rails"
gem "pg"
gem "mini_racer"
gem "opsgenie-schedule"
gem "puma"
gem "rollbar"
gem "rails", "~> 7.1.0"
gem "sass-rails", "~> 6.0"
gem "turbolinks", "~> 5"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "redis-rails"
gem "redis", "~> 4"

group :development do
  gem "listen", ">= 3.0.5", "< 3.9.1"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.1.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "factory_bot"
  gem "launchy"
  gem "selenium-webdriver"
  gem "timecop"
  gem "webmock"
end

group :development do
  gem "better_errors"
  gem "html2haml"
  gem "rails_layout"
  gem "spring-commands-rspec"
end

group :development, :test do
  gem "brakeman"
  gem "bullet"
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem "pry"
  gem "rspec-rails"
  gem "standard"
end
