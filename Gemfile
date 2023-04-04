source 'https://rubygems.org'
ruby '2.2.4'
gem 'rails', '~> 6.1.7', '>= 6.1.7.3'
gem 'sass-rails', '~> 6.0', '>= 6.0.0'
gem 'uglifier', '>= 2.7.2'
gem 'coffee-rails', '~> 4.2.2'
gem 'jquery-rails', '>= 4.4.0'
gem 'jquery-ui-rails', '>= 6.0.0'
gem 'jbuilder', '~> 2.6', '>= 2.6.4'
gem 'yell-rails'
gem 'coderay', '~> 1.1'
gem 'kaminari', '~> 1.2', '>= 1.2.1' # adds pagination to ActiveModels
gem 'bootstrap-sass', '>= 3.4.0'
gem 'devise', '>= 4.7.1'
gem 'haml-rails', '>= 1.0.0'
gem 'pg'
gem 'simple_form', '>= 5.0.0'
gem 'momentjs-rails', '>= 2.10.3'
gem 'bootstrap3-datetimepicker-rails', '~> 4.7.14'
gem 'modulejs-rails'
gem 'react-rails', '~> 1.3', '>= 1.3.1'
gem 'font-awesome-rails', '>= 4.7.0.6'
gem 'bootswatch-rails'
gem 'pry-rails'
gem 'i18n-js', github: 'fnando/i18n-js'
gem 'twitter-bootstrap-rails-confirm'
gem 'hbw', path: File.join(File.dirname(__FILE__), 'hbw')
gem 'asset_symlink', '>= 0.3.2'
gem 'apitome'
gem 'dry-container'
gem 'dry-auto_inject'
gem 'dry-validation'
gem 'thin', '>= 1.7.0'

group :oracle do
  gem 'ruby-oci8', '2.2.1'
end

group :development do
  gem 'better_errors', '>= 2.8.0'
  gem 'binding_of_caller'
  gem 'capistrano', '~> 3.4', '>= 3.4.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-postgresql'
  gem 'capistrano-rails-console'
  gem 'capistrano-db-tasks', require: false
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'html2haml', '>= 2.2.0'
  gem 'quiet_assets'
  gem 'rails_layout'
  gem 'spring-commands-rspec'
  gem 'ruby_parser'
end

group :development, :test, :staging do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails', '>= 3.5.0'
  gem 'rspec-mocks'
  gem 'translit'
  gem 'web-console', '~> 2.2', '>= 2.2.1'
  gem 'spring'
  gem 'rspec_api_documentation', '~> 4.8', '>= 4.8.0'
  gem 'raddocs', '~> 2.2', '>= 2.2.0'
  gem 'rubocop', '>= 0.49.0'
  gem 'debbie', '>= 2.0.0'
  gem 'pry-byebug'
  gem 'rspec_junit_formatter'
end

group :production, :staging do
  gem 'unicorn'
end

group :test do
  gem 'temping'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'poltergeist'
  gem 'capybara-screenshot'
end
