source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.2.0'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

group :development,:test do
  gem 'sqlite3'
  gem 'rspec-rails'
end
group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'cucumber-rails'
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

gem 'sass-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
