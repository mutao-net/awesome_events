source 'https://rubygems.org'

gem 'rails', '7.1.0'
gem 'sqlite3', '~> 1.3.9'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '~> 2.7.2'
gem 'coffee-rails', '~> 4.2.2'
gem 'jquery-rails', '~> 4.0.1'
gem 'turbolinks', '~> 5.0.0'
gem 'omniauth', '~> 2.1.0'
gem 'omniauth-twitter', '~> 1.1.0'
gem 'kaminari', '~> 0.16.0'
gem 'kaminari-bootstrap', '~> 3.0.1'
gem "ransack", "~> 1.3.0"
gem 'carrierwave', '~> 0.11.0'
gem 'mini_magick', '~> 4.9.4'

group :development do
  gem "capistrano", "3.2.0"
  gem "capistrano-rails", ">= 1.1.2"
  gem "capistrano-bundler", ">= 1.1.3"
  gem "capistrano3-unicorn", ">= 0.2.1"
  gem 'spring'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0.0.beta', github: 'rspec/rspec-rails'
  gem 'rspec-core', '~> 3.0.0.beta', github: 'rspec/rspec-core'
  gem 'rspec-expectations', '~> 3.0.0.beta', github: 'rspec/rspec-expectations'
  gem 'rspec-mocks', '~> 3.0.0.beta', github: 'rspec/rspec-mocks'
  gem 'rspec-support', '~> 3.0.0.beta', github: 'rspec/rspec-support'
  gem 'factory_girl_rails', '~> 4.5.0'
end

group :test do
  gem 'shoulda-matchers', '~> 2.6.2'
  gem 'capybara', '~> 2.3.0'
  gem 'poltergeist', '~> 1.5.1'
  gem 'database_cleaner', '~> 1.2.0'
end

group :staging, :production do
  gem 'unicorn'
end
