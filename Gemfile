source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'bootsnap', require: false
gem 'bootstrap', '~> 5.1', '>= 5.1.3'
gem 'importmap-rails'
gem 'jbuilder'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.3'
gem 'rubocop'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]

group :development do
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'sqlite3'
  gem 'web-console'
end

group :production do
  gem 'pg', '~> 1.3', '>= 1.3.5'
  gem 'rails_12factor', '~> 0.0.3'
end
