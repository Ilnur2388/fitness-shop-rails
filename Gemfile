source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "rails", "~> 7.0.8"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
# gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem 'rubocop', '~> 1.57', '>= 1.57.1'
  gem 'rubocop-performance', '~> 1.19', '>= 1.19.1'
  gem 'rubocop-rspec', '~> 2.24', '>= 2.24.1'
end

group :test do
  gem 'rspec', '~> 3.12'
  gem "capybara"
  gem "selenium-webdriver"
end

gem "tailwindcss-rails", "~> 2.0"
