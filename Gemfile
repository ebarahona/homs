source 'https://rubygems.org'
ruby '2.2.4'
gem 'rails', '~> 5.2.4', '>= 5.2.4.3'
gem 'sass-rails', '~> 5.0', '>= 5.0.5'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'jquery-rails', '>= 4.1.1'
gem 'jquery-ui-rails', '>= 5.0.5'
gem 'jbuilder', '~> 2.6', '>= 2.6.4'
gem 'yell-rails', '>= 2.0.0'
gem 'coderay', '~> 1.1'
gem 'kaminari', '~> 0.16', '>= 0.16.3' # adds pagination to ActiveModels
gem 'bootstrap-sass'
gem 'devise', '>= 4.4.2'
gem 'haml-rails', '>= 0.9.0'
gem 'pg'
gem 'simple_form', '>= 4.0.0'
gem 'momentjs-rails', '>= 2.10.3'
gem 'bootstrap3-datetimepicker-rails', '~> 4.7.14'
gem 'modulejs-rails', '>= 1.9.0.1'
gem 'react-rails', '~> 1.3', '>= 1.3.1'
gem 'font-awesome-rails', '>= 4.7.0.4'
gem 'bootswatch-rails', '>= 3.3.5'
gem 'pry-rails'
gem 'i18n-js', github: 'fnando/i18n-js'
gem 'twitter-bootstrap-rails-confirm'
gem 'hbw', path: File.join(File.dirname(__FILE__), 'hbw')
gem 'asset_symlink', '>= 0.3.1'
gem 'apitome', '>= 0.1.0'
gem 'dry-container'
gem 'dry-auto_inject'
gem 'dry-validation'
gem 'thin'

group :oracle do
  gem 'ruby-oci8', '2.2.1'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'capistrano', '~> 3.1'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-postgresql'
  gem 'capistrano-rails-console'
  gem 'capistrano-db-tasks', require: false
  gem 'capistrano-rvm', '~> 0.1.1'
  gem 'html2haml'
  gem 'quiet_assets', '>= 1.1.0'
  gem 'rails_layout'
  gem 'spring-commands-rspec'
  gem 'ruby_parser'
end

group :development, :test, :staging do
  gem 'factory_girl_rails', '>= 4.5.0'
  gem 'faker'
  gem 'rspec-rails', '>= 3.5.0'
  gem 'rspec-mocks'
  gem 'translit'
  gem 'web-console', '~> 2.2', '>= 2.2.1'
  gem 'spring'
  gem 'rspec_api_documentation', '~> 4.4', '>= 4.4.0'
  gem 'raddocs', '~> 0.4'
  gem 'rubocop'
  gem 'debbie', '>= 2.0.0'
  gem 'pry-byebug'
  gem 'rspec_junit_formatter'
end

group :production, :staging do
  gem 'unicorn'
end

group :test do
  gem 'temping', '>= 3.3.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'poltergeist'
  gem 'capybara-screenshot'
end
