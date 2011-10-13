require 'rbconfig'
HOST_OS = Config::CONFIG['host_os']

source 'http://rubygems.org'
gem 'rails', '3.1.1'
gem 'rack', '1.3.3'
gem 'sqlite3'
gem 'jquery-rails'
gem "haml", ">= 3.1.2"
gem "devise", ">= 1.4.7"
gem "frontend-helpers"
gem "activeadmin"
gem "simple_form"

if HOST_OS =~ /linux/i
  gem 'therubyracer', '>= 0.8.2'
end

group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem "haml-rails", ">= 0.3.4"
  gem "rspec-rails", ">= 2.6.1"
  gem "factory_girl_rails", ">= 1.2.0"
  gem "cucumber-rails", ">= 1.1.1"
  gem "capybara", ">= 1.1.1"
  gem "database_cleaner", ">= 0.6.7"
  gem "launchy", ">= 2.0.5"
  gem "guard", ">= 0.6.2"
  gem 'rb-fsevent'
  gem 'growl'
  gem "guard-bundler", ">= 0.1.3"
  gem "guard-rails", ">= 0.0.3"
  gem "guard-livereload", ">= 0.3.0"
  gem "guard-rspec", ">= 0.4.3"
  gem "guard-cucumber", ">= 0.6.1"
  gem "rails-footnotes", ">= 3.7"
  gem "itslog"
  gem 'web-app-theme'

  case HOST_OS
    when /darwin/i
      gem 'rb-fsevent'
      gem 'growl'
    when /linux/i
      gem 'libnotify'
      gem 'rb-inotify'
    when /mswin|windows/i
      gem 'rb-fchange'
      gem 'win32console'
      gem 'rb-notifu'
  end
end


