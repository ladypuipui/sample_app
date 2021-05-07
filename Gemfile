source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'

gem 'rails', '6.1.3.1'
gem 'puma', '5.2.2'
gem 'sass-rails', '6.0.0'
gem 'webpacker', '5.2.1'
gem 'turbolinks', '5.2.1'
gem 'jbuilder', '2.11.2'
gem 'bootsnap', '1.7.3', require: false
gem 'bootstrap-sass', '3.4.1'
gem 'rexml'
gem 'bcrypt',         '3.1.13'

group :production do
  gem 'pg', '~> 1.1'
end

group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '4.1.0'
  gem 'rack-mini-profiler', '2.0.0'
  gem 'listen', '3.5.1'
  gem 'spring', '2.1.1'
end

group :test do
  gem 'capybara', '3.35.3'
  gem 'selenium-webdriver', '3.142.7'
  gem 'webdrivers','4.6.0'
  gem 'rails-controller-testing', '1.0.4'
  gem 'minitest',                 '5.14.4'
  gem 'minitest-reporters',       '1.3.8'
  gem 'guard',                    '2.16.2'
  gem 'guard-minitest',           '2.4.6'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
