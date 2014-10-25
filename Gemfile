source "https://rubygems.org"

ruby "2.1.2"

gem "active_model_serializers"
gem "analytics-ruby", "~> 2.0.10", require: "segment/analytics"
gem "angularjs-rails"
gem "attr_extras"
gem "bourbon"
gem "coffee-rails"
gem "coffeelint"
gem "font-awesome-rails"
gem "haml-rails"
gem "high_voltage"
gem "jquery-rails"
gem "jshintrb"
gem "neat"
gem "newrelic_rpm"
gem "octokit"
gem "omniauth-github"
gem "paranoia", "~> 2.0"
gem "pg"
gem "rails", "4.1.5"
gem "resque", "~> 1.22.0"
gem "resque-retry"
gem "resque-sentry"
gem "rubocop", "0.26.1"
gem "sass-rails", "~> 4.0.3"
gem "sentry-raven"
gem "stripe"
gem "uglifier", ">= 1.0.3"
gem "unicorn"

group :staging, :production do
  gem "rails_12factor"
end

group :development, :test do
  gem "byebug"
  gem "foreman"
  gem "konacha"
  gem "poltergeist"
  gem "rspec-rails", ">= 3.0"
end

group :test do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-rails'
  gem "capybara", "~> 2.4.4"
  gem "capybara-webkit"
  gem "database_cleaner"
  gem "factory_girl_rails"
  gem "launchy"
  gem "shoulda-matchers"
  gem "webmock"
end
