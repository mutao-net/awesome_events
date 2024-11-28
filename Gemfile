source 'https://rubygems.org'

gem 'rails', '7.0.0'
gem 'sqlite3', '~> 1.3.9'
gem 'sass-rails', '~> 6.0.0'
gem 'uglifier', '~> 2.7.2'
gem 'coffee-rails', '~> 4.0.1'
gem 'jquery-rails', '~> 4.4.0'
gem 'turbolinks', '~> 5.0.0'
gem 'omniauth', '~> 2.0.0'
gem 'omniauth-twitter', '~> 1.1.0'
gem 'kaminari', '~> 1.0.0'
gem 'kaminari-bootstrap', '~> 3.0.1'
gem "ransack", "~> 2.3.1"
gem 'carrierwave', '~> 2.2.6'
gem 'mini_magick', '~> 4.9.4'

group :development do
  gem "capistrano", "3.1.0"
  gem "capistrano-rails"
  gem "capistrano-bundler"
  gem "capistrano3-unicorn"
  gem 'spring'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0.0.beta', github: 'rspec/rspec-rails'
  gem 'rspec-core', '~> 3.0.0.beta', github: 'rspec/rspec-core'
  gem 'rspec-expectations', '~> 3.0.0.beta', github: 'rspec/rspec-expectations'
  gem 'rspec-mocks', '~> 3.0.0.beta', github: 'rspec/rspec-mocks'
  gem 'rspec-support', '~> 3.0.0.beta', github: 'rspec/rspec-support'
  gem 'factory_girl_rails', '~> 4.4.1'
end

group :test do
  gem 'shoulda-matchers', '~> 2.6.0'
  gem 'capybara', '~> 2.3.0'
  gem 'poltergeist', '~> 1.5.1'
  gem 'database_cleaner', '~> 1.2.0'
end

group :staging, :production do
  gem 'unicorn'
end
