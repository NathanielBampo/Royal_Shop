source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "redis", "~> 4.0"
# gem "kredis"
# gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
# gem "sassc-rails"
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-rails'
  gem "pg", "~> 1.1"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "web-console"
  gem 'rspec-rails', '~> 6.0.0'
end

group :development do
  gem 'guard-rspec'
  gem 'guard-minitest'
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  # gem "rack-mini-profiler"
  gem "spring"
end

group :production do
end
