source 'https://rubygems.org'

ruby '2.3.4'

gem 'rails', '4.2.1'
gem 'bootstrap-sass', '~> 3.4.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'high_voltage', '~> 2.2.1'

group :development, :production do
  gem 'thin', :group => 'production'
end

group :production do
  gem "rails_12factor"
end

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'better_errors'
  gem 'binding_of_caller'
end
