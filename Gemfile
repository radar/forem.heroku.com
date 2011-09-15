source 'http://rubygems.org'

gem 'rails', '3.1.0'

gem 'will_paginate'
gem 'devise'
if ENV['USE_LOCAL_FOREM']
  gem 'forem', :path => "~/Sites/side_projects/forem" 
else
  gem 'forem', :git => "git://github.com/radar/forem.git"
end
# gem 'forem-theme-orange', :git => "git://github.com/radar/forem-theme-orange"
gem 'forem-theme-twist', :path => "~/Sites/side_projects/forem-theme-twist"

group :assets do
  gem 'sass-rails', " ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'dragonfly', '0.9.5'

group :development do
  gem 'sqlite3'
  gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'ruby-prof'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :production do
  gem 'pg'
end
