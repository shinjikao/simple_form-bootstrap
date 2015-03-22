source 'http://rubygems.org'
ruby '2.1.5'
gem 'simple_form'
gem 'rails', '~> 4.1.0'

gem 'json'
gem 'thin'

gem 'uglifier'
gem 'jquery-rails'
gem 'sass-rails', '~> 4.0.2'
gem 'bootstrap-sass', '~> 3.3.0'


group :development do
  gem 'sqlite3'
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end

group :production do
  #gem 'pg'
  gem 'sqlite3'
  gem 'rails_12factor'
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end


gem 'sqlite3', :groups => [:test, :development]
