source 'https://rubygems.org'

# Rails 5
gem 'rails',      github: 'rails/rails'
gem 'turbolinks', github: 'rails/turbolinks'
gem 'devise',     github: 'twalpole/devise'
#gem 'devise',     github: 'twalpole/devise', branch: 'rails5'
gem 'rails-controller-testing'

gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jbuilder'
gem 'sdoc', group: :doc
gem 'overcommit'

group :development do
  gem 'web-console'
#, github: 'rails/web-console'
end

group :development, :test do
  gem 'byebug'
  gem 'spring'

  # ADDED ......................................................
  # Rails 5
  gem 'rspec-rails', '3.5.0.beta1'

  # ADDED ......................................................
  gem 'factory_girl_rails'
  gem 'capybara'
#HID/FIXME:  gem 'guard-rspec'
  gem 'spring-commands-rspec'
  gem 'vcr'
end

group :test do
  # ADDED ......................................................
  gem 'webmock'
end

