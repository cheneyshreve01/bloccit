source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'

group :production do
  # Use pg as the production database for Active Record
  gem 'pg'
  gem 'rails_12factor'
end

group :development do
  # Use sqlite3 as the development database for Active Record
  gem 'sqlite3'
end

group :development do
  gem 'rspec-rails', '~> 3.0'
  gem 'rails-controller-testing'
  gem 'pry-rails'
end

gem 'font-awesome-rails'
gem 'bootstrap-sass'
# gem 'rails-controller-testing'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use jQuery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'thor', '0.19.1'

group :development do
  gem 'listen', '~> 3.0.5'
end
