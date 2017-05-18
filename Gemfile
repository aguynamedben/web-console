source 'https://rubygems.org'

gemspec

gem 'rails', git: 'https://github.com/rails/rails.git'
gem 'arel', git: 'https://github.com/rails/arel.git'
gem 'rack', git: 'https://github.com/rack/rack.git'

group :development do
  platform :ruby do
    gem 'byebug'
  end
  gem 'puma'
end

group :test do
  gem 'rake'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end
