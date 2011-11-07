source 'http://rubygems.org'

gem 'rails', '3.1.1'#, :path => "vendor/rails"
# gem 'assets', :path => "~/Sites/side_projects/assets"

gem 'will_paginate'
gem 'devise'
if ENV['USE_LOCAL_FOREM']
  gem 'forem', :path => "~/Sites/side_projects/forem"
  gem 'forem-theme-twist', :path => "~/Sites/side_projects/forem-theme-twist"
  gem 'forem-rdiscount', :path => "~/Sites/side_projects/forem-rdiscount"
else
  gem 'forem', :git => "git://github.com/radar/forem.git"
  gem 'forem-theme-twist', :git => "git://github.com/radar/forem-theme-twist"
  gem 'forem-rdiscount', :git => "git://github.com/radar/forem-rdiscount"
end

group :assets do
  gem 'sass-rails', " ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'dragonfly', '0.9.5'

group :development do
  gem 'sqlite3'
  gem 'ruby-prof'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :production do
  gem 'pg'
end

gem 'json'
