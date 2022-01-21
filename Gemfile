# frozen_string_literal: true

source 'https://rubygems.org'

gem 'coffee-rails', '4.2.2'
gem 'jbuilder',     '2.7.0'
gem 'jquery-rails', '4.3.1'
gem 'puma',         '3.9.1'
gem 'rails',        '5.1.6'
gem 'sass-rails',   '5.0.6'
gem 'turbolinks',   '5.0.1'
gem 'uglifier',     '3.2.0'

group :development, :test do
  gem 'byebug',  '9.0.6', platform: :mri
  gem 'sqlite3', '1.3.13'
end

group :development do
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
  gem 'web-console',           '3.5.1'
  # Code quality
  gem 'rubocop', '~> 1.16', require: false
  gem 'rubocop-rails', '~> 2.10', require: false
end

group :production do
  gem 'pg', '0.20.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
